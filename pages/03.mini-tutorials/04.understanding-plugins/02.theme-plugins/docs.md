---
title: 'Theme Plugins'
taxonomy:
    category:
        - docs
visible: true
---

---

### Figuring out which plugins a theme supports

! This section involves interacting with the file system and looking at code. You will not have to interact directly with the code.

Good documentation is often the sign of code. However, you may find yourself in love with a theme that does not have very thorough documentation. In that case, figuring out which plugins it supports can be difficult. The most cumbersome method would be to install every plugin and see if it changes your website. A perhaps more thorough (and certainly less cumbersome) method would be looking through the various templates provided by the theme.

1. Open up your file system. If using Reclaim Hosting/OU Create, the File Manager can be found under the Files heading on your dashboard.
2. Go to your Grav install and find `users/themes/your-theme-name/templates`. You will see several files ending in .html.twig and probably at least one folder (which will hold more templates).
3. Open up the first file.
4. Search for `config.plugins`. This statement will generally show up in an if statement like so: `if config.plugins.plugin-name.enabled`, but it may not.
5. Note the names of any plugins that come up the search. These plugins are used by the theme if installed.
6. Repeat steps 4 and 5 for each of the files in the templates folder, and then for the files of each folder in the templates folder.