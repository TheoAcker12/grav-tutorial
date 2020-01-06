---
title: 'Modular Header'
taxonomy:
    category:
        - docs
visible: true
---

---

In the Quark theme, there are three types of modular templates: Hero, Features, and Text. You may recall the term 'hero' from working on the Blog page. A hero is essentially a large image with text on top. The Blog template has a hero header built in, which the content goes on top of. The Modular template does not, so if we want a hero-style header, we will have to add one.

If we try to add the page as normal, none of the three modular templates I mentioned are options. Instead, we have to go click the down arrow next to the add button and choose _add modular_.

- screenshot

Now we can choose the Hero template.

- screenshot

It may be tempting to name the page Header, since that is the purpose it will serve. Unfortunately, this will create issues within the template, because there is already a section called _header_. We do not want this to overwrite that, or we will lose our navigation bar!

Although the automatic folder name does not show an underscore at the front, there is no need to worry. When the folder is created it will have an underscore.

Before we add any content, there is an important order of business. When adding subpages, Grav does not like to include numeric prefixes. That is, if you go to the Home page, you can see under the Advanced tab that there are two sortable pages.

- screenshot

This is because numeric prefixes are enabled, which determines the order pages will be displayed in the navigation.

- screenshot

However, going back to our new Homepage Header, it appears that numeric prefixes are not enabled. We need to fix that. Giving modular folders numeric prefixes means that the modular parent page knows in which order to show the content from those pages. That is pretty important!

We can add some content, of course. This will display on top of whatever image we decide to add, so we don't want to do too much. I am going with just a header and a link. The extra things after the "?" provide some html settings. The classes will be noticed by the theme and used to display the link as a button, and the target variable will mean the link is opened in a new page.

- screenshot

We can also add an image. We do not need to explicitly set this image as the hero image, although it does not hurt. As with the blog page, there are also options for hero classes that will define how the hero is displayed.

That looks pretty good.

- screenshot

