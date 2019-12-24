---
title: Plugins
taxonomy:
    category:
        - docs
visible: true
---

---
As mentioned previously, plugins provide additional functionality to your website. To see a list of the plugins you can add, click on the _Add_ button at the top right of the Plugins section of your admin panel.
! If you get a message that you cannot connect to the gpm then you most likely need to update Grav.

## Picking Plugins
So how do you decide which plugins to use? Unless you plan to do some customization of your own, most likely you will only be interested in plugins that your chosen theme already interacts with. Many of the available themes have sections that will only turn on if the corresponding plugin is installed.

Determing which plugins a theme supports can be a bit of pain, however. Some themes will state which plugins they support in their Readmes. If your chosen theme does not list all supported plugins in its Readme, you can investigate the templates themselves (described further below). You can also choose to install a promising plugin and then see if anything in your website changes.

Some commonly supported plugins: Breadcrumbs, Feed, Form, Pagination, SimpleSearch, Taxonomy List, TNT Search

Many plugins do not need to be supported directly by a theme, so it is worth browsing through the available plugins and reading the short description for each.

Any plugin you install may have additional configuration options. These will show up on the plugin page below the link to the Readme after installation.

### Figuring out which plugins a theme supports

! This section involves interacting with the file system and looking at code. You will not have to interact directly with the code.

Good documentation is often the sign of code. However, you may find yourself in love with a theme that does not have very thorough documentation. In that case, figuring out which plugins it supports can be difficult. The most cumbersome method would be to install every plugin and see if it changes your website. A perhaps more thorough (and certainly less cumbersome) method would be looking through the various templates provided by the theme.

1. Open up your file system. If using Reclaim Hosting/OU Create, the File Manager can be found under the Files heading on your dashboard.
2. Go to your Grav install and find `users/themes/your-theme-name/templates`. You will see several files ending in .html.twig and probably at least one folder (which will hold more templates).
3. Open up the first file.
4. Search for `config.plugins`. This statement will generally show up in an if statement like so: `if config.plugins.plugin-name.enabled`, but it may not.
5. Note the names of any plugins that come up the search. These plugins are used by the theme if installed.
6. Repeat steps 4 and 5 for each of the files in the templates folder, and then for the files of each folder in the templates folder.