---
title: 'Non-Theme Plugins'
taxonomy:
    category:
        - docs
visible: true
---

---

Information about understanding how to use:

When examining the Readme of a plugin, most likely the instructions for use will involve Twig/html, markdown, or yaml.

Twig and html (example from SimpleSearch):
```twig

{% extends 'partials/simplesearch_base.html.twig' %}

{% block content %}
    <div class="content-padding">
    <h1 class="search-header">Search Results</h1>
    <h3>Query: "{{ query }}" - Found {{ search_results.count }} {{ 'Item'|pluralize(search_results.count) }}</h3>

    {% for page in search_results %}
        {% include 'partials/simplesearch_item.html.twig' with {'page':page} %}
    {% endfor %}
    </div>
{% endblock %}
```
If you see this, you can ignore it. This is the code used in templating.

Markdown (example from Diagrams):
```md
[sequence]
A->B:Hi C for me !
B-->A:With pleasure
B->C:A says hello
[/sequence]
```
This can be included directly in the pages you write.

Yaml (example from Email):
```yaml
title: Custom form

form:
  name: custom_form
  fields:

    # Any fields you'd like to add to the form:
    # Their values may be referenced in email actions via '{{ form.value.FIELDNAME|e }}'

  process:
    email:
      subject: "[Custom form] {{ form.value.name|e }}"
      body: "{% include 'forms/data.txt.twig' %}"
      from: sender@example.com
      from_name: 'Custom sender name'
      to: recipient@example.com
      to_name: 'Custom recipient name'
      content_type: 'text/plain'
      process_markdown: true
```
This is the format that the frontmatter of each of your pages will be written in. In normal editing mode, the admin panel takes care of the frontmatter for you, but if you need to edit it directly in order to use a specific plugin, you can always switch to expert mode temporarily.

If the plugin has configurable options, those may also be shown using yaml. You can generally ignore those, as the admin panel will provide a user interface to interact with these options when you click on the plugin.