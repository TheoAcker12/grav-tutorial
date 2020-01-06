---
title: 'The Modular Page'
taxonomy:
    category:
        - docs
visible: true
---

---

Since we want the modular page to be our home page, we will need to replace the current home page. First we have to delete all the content from the content area. Since modular pages hold no content of their own, the content is completely unnecessary.

We also have to change the template the page is using. On the Advanced tab, change the template from default to modular and click _Save_.

- screenshot

Unfortunately there is one issue we will have to deal with. Because the page was originally using the default template, it is not setup properly. Looking at the Content tab, there is a section below Page Media called Modular Setup. It looks like it should, with `NOCLIP @self.modular` in the Items box. This is what we want.

- screenshot

However, if we switch to expert mode, there is nothing in the frontmatter.

- screenshot

Back in normal mode, make sure to click on the box with your cursor and then save. Nothing else is required. If you switch to expert mode, you should now see this:

- screenshot or code block

This is a potential issue any time we change the template of a page. Although the fields in the editor's normal mode will typically auto-fill, they may not actually be set in the frontmatter. Clicking on the field before saving can fix that.