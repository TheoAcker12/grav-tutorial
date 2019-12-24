---
title: Themes
taxonomy:
    category:
        - docs
visible: true
---

---
Themes determine the look and feel of your website, which makes them very important. To see a list of the themes you can add, click on the _Add_ button at the top right of the Themes section of your admin panel.
! If you get a message that you cannot connect to the gpm then you most likely need to update Grav.

## Choosing a Theme
Although themes share many similarities with plugins, one major difference is that you can only have one active theme. Since this one theme is going to determine how users experience your website, it is worth spending some time and being picky. There are a couple of things you need to decide or at least start thinking about now.

* **How much customization do you want or plan to do?**
You may already have an idea of how absolutely fabulous your website is going to look. Unfortunately, web design is rarely (read never) as simple as we would like it to be. The more detailed your requirements are, the more work you will have to put in to design and then maintain the website. Customizing themes are discussed in more detail further on. If you are not eager to deal with html and css, among other things, you may want to hold back on your expectations.

* **What is the purpose of your website?** 
Themes determine more than just the basic visuals. Each theme has some number of page templates that can be used in various ways. So if you want a website for blogging, you will want a theme that has a template for blogs. A theme that supports blogging will likely also support plugins like Taxonomy List (that allows you to filter your posts by tags) and SimpleSearch. 

The next step is taking a look at the available themes. There are several ways to get an idea of how the theme will look.
1. **Theme images.** Most themes will have a thumbnail image of what the theme will look like when you browse themes in the admin panel.
2. **Readmes.** All themes must have a Readme file. Sometimes there may be nothing of value in the Readme, but other times the Readme may document how you can use the theme. This may give you an idea of what plugins are supported or how make use of various theme features.
3. **Templates.** In addition to a link to the Readme, themes must also have a link to a GitHub repository. You can follow this link and go to the templates folder to get a brief overview of the types of templates available. Ideally this information will be included in the Readme.
4. **Demo sites.** Some themes have a demo site you can explore that was built using the theme. This is a good way to see how it can all come together, what features the theme has, and what the different available templates look like. After all, one image will generally only correspond to one page, so for a multi-page site it will rarely be sufficient.
5. **Skeletons.** This is the holy grail of themes (along with a well-documented Readme). [This site](https://getgrav.org/downloads/skeletons) lists the available skeletons for Grav. These may include links to demo websites, but more importantly they will include links to a github repository containing a very important folder called pages. You can ignore just about everything else, although the config folder may occasionally be useful. You can choose whatever method you like to move this content into your website, or you can simply investigate it from the repository. The value of this is that you can see how the pages were built and get an idea for how to incorporate the available features.
6. **Trial and error.** Failing all else, you can also add the theme, activate it, and then try making some pages with the various template options. At the end of the day you will have to do this to some degree, but hopefully you will be able to investigate some of the above options first.

## Using the Theme
Once you have added a theme you will have to activate it in order to use it. Customizable options work the same as in plugins. If there are any, they will become available after installation.

Using the various templates will be covered in the next section on Pages.


This website was built using the Learn2 with Git Sync theme.