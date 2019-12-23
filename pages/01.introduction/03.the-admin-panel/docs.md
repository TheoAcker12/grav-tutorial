---
title: 'The Admin Panel'
taxonomy:
    category:
        - docs
visible: true
---

---
Familiarity with the admin panel is important, as this is where you will spend most of your time making your website. It can be accessed by going to `your-site-URL/admin`. You will then log in using the username and password you selected when installing Grav. Once you have logged in you will see several options on the left sidebar: Dashboard, Configuration, Pages, Plugins, Themes, Tools, and Logout.

## Dashboard
This is where you go on login. By default tthe dashboard will show you maintenance, statistics, notifications, a news feed, and latest page updates. You can change this by configuring the admin plugin, but for now this is fine. What you should do immediately is update Grav (after checking for updates). Most likely you will need to do a general update, which will update plugins and themes, and a Grav update, which will update Grav to the latest version. OU Create currently recognizes Grav 1.6.16, but at the time of writing Grav is up to 1.6.19.

Making certain that you are up-to-date is essential. You do not want to deal with the frustration of trying to solve a seemingly unsolvable error, only to find out that you are not using the latest version of Grav and that updating fixes all your problems. (I speak from experience.)

## Configuration
For anyone digging into the file system, this is the user interface for the various .yaml files found in the config or user/config folders. For anyone _not_ digging in the file system, this is where you can check on and change various settings for your website.

I would not advise going through all of the settings here. There are a lot of them, and for the most part the default values will be fine. As a general rule I would not recommend changing anything unless you know what you are doing. Fortunately, configuration defaults to the site page, which is the one place you are most likely to want to make changes. You should scan through the site settings, both to make any changes that need to be done now and to note any areas that might need to be changed later.

## Pages
This is where you will spend the majority of your time. We will come back to it later.

## Plugins
The Plugins section is where you can access information about your plugins, toggle plugins off and on, and add or remove plugins. Plugins provide extra functionality to your website. For example, the admin plugin is what provides the handy user interface you are using to manage your website. Without it, you would be stuck interacting directly with the command line and file system.

You may see that you have a few other initial plugins. Clicking on a plugin will provide some information about the plugin, as well as any configurable options. All plugins will also have a link to their Readme file. Sometimes this file will have detailed instructions of what the plugin does and how to use it. Other times it will not be very helpful at all. When in doubt, always check the Readme first!

## Themes
The Themes section is very similar to the Plugins section. Themes will determine how your website ultimately looks. Your theme will define various templates that you can fill out in the Pages section, as well as how those pages will interact with other pages or plugins. As with plugins, all themes will have a Readme file, but not all Readme files will be helpful.

## Tools
This is where you can manage backup settings, among other things. You do not need to worry about any of this for now.

## Logout
This is not actually a separate tab. It just logs you out.