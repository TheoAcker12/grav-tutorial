---
title: 'Themes and Plugins'
media_order: 'add-plugins.png,add-theme.png,archives-configuration.png,install-archives.png,theme-config.png,themes-tab.png'
taxonomy:
    category:
        - docs
visible: true
---

---

Themes and plugins are both very important. Every website has one theme, which defines how the site looks and feels. The theme may also interact with various plugins, such as by adding a search bar if the plugin _SimpleSearch_ is enabled. There are many available plugins, each of which adds some type of functionality to your website. In fact, the admin panel we are using is actually a plugin itself.

! When going to add themes or plugins, if you get a message that you cannot connect to the gpm, you probably need to update Grav

## Themes

First, we need to choose a theme. We will start by going to the _Themes_ tab on the administration panel.

![themes-tab](themes-tab.png)

To see a list of themes we can add, click on the _Add_ button at the top right.

![add theme button](add-theme.png)

!!! The **[Themes chapter](https://learn.getgrav.org/16/themes)** in the Grav documentation is very technical, but you may want to check out the section on themes in the **[Adminstration Panel chapter](https://learn.getgrav.org/16/admin-panel/themes)**.

There are a lot of available themes. If you click on one of them, you will see a variety of information including a linke to a Readme file, and possibly a link to a demo website. These are both worth examining if you are considering using that theme. [Skeletons](https://getgrav.http://grav.ds-tutorials.oucreate.com/mini-tutorials/understanding-themes/theme-skeletons/downloads/skeletons) can also be a helpful resource for understanding themes, but they will be covered in the mini tutorials.

For this tutorial we will actually use the default theme, so we can go back to the _Themes_ tab without installing anything.

Clicking on the _Quark_ theme will show us the information page for the theme. There is a link to the Readme file that contains more detailed information, and right under it are a number of configuration options for various aspects of the theme. For now, we will leave them as they are.

![Quark theme configuration](theme-config.png)

## Plugins

Some themes support certain plugins. Common suspects include _Breadcrumbs_, _Pagination_, _SimpleSearch_, _Taxonomy List_, and _TNT Search_. Ideally your chosen theme will have a detailed Readme that lists supported plugins. If it does not, I describe how to manually find out which plugins the theme uses in the following [mini tutorial](http://grav.ds-tutorials.oucreate.com/mini-tutorials/understanding-plugins/theme-plugins). There are also many plugins that do not require theme support. The best way to find out how to use a plugin is to look through the provided Readme.

!!! The **[Plugins chapter](https://learn.getgrav.org/16/plugins)** in the Grav documentation is very technical, but you may want to check out the section on plugins in the **[Adminstration Panel chapter](https://learn.getgrav.org/16/admin-panel/plugins)**.

Unfortunately, while the Readme for _Quark_ is very helpful, it does not describe what plugins it automatically supports. However, we will install several of the most commonly supported plugins.

To start with, we will need to go to the _Plugins_ tab on the admin panel and the click the _Add_ button.

![add plugin](add-plugins.png)

Since there are a lot of plugins, it is easiest to search for a plugin you know you want by typing in the name. We will start with the _Archives_ plugin.

![install archives plugin](install-archives.png)

When the installation has finished, the admin panel will take us to the information and configuration page for the plugin, just like it did when we installed the theme. Again, you will see both a link to the Readme for the plugin and the various configuration options available. Now we have to install the _Breadcrumbs_, _Feed_, _Pagination_, _Random_, _Related Pages_, _SimpleSearch_, and _Taxonomy List_ plugins. These are installed exactly the same way that we installed _Archives_.

Those are quite a few plugins, especially if you are not sure what they do yet. One easy option for experimenting with how they affect the website and theme interactions is to toggle the plugins on and off. However, we will need to add content to the website before that does anything useful for us.

![plugin toggles](toggle-plugins.png)
