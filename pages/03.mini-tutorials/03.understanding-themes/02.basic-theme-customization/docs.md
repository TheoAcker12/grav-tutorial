---
title: 'Basic Theme Customization'
taxonomy:
    category:
        - docs
visible: true
---

---

Ideally your theme will have all the configuration options you need built into it.
It probably won't.

- Grav has a [theme tutorial](https://learn.getgrav.org/16/themes/theme-tutorial) that guides you through creating a new theme using pure.css framework
- If you don't want to do anything fancy, that may not be for you
- also that probably wouldn't end up being basic

- For this tutorial we will assume that you want to make some minor modifications to the theme that you are using, but otherwise you like that theme
- If you make the modifications directly to the theme files, you may be disappointed when the theme is updated and all of your changes are lost
- Therefore, always set up a new theme that inherits from your old one
- The way it works is that when Grav needs a specific template, for example, it will look in your theme. If the file it wants isn't there, it will then look in the theme you are inheriting from
- needless to say this is quite useful

To set up theme inheritance:
- first install the devtools plugin
- then you need to go to the terminal on Reclaim Hosting/OU Create
- enter the install directory
- type `bin/plugin devtools new-theme`
- you probably won't get a weird permission error, but if you do, here is how to fix it - instructions on chmod
- fill out the requested fields
- once you've done that, you can leave the command line, everything else will use the admin panel and/or the file system

- those are the first steps whether you are doing basic or advanced theme modification
- advanced theme modification would be anything involving templates
- basic will just involve css
- maybe could add some id or class tags to the html of a template as well
- anything above the advanced as specified and you'll need to use the various documentations - this tutorial is for beginners, not experienced coders, sorry

Modifying the css:

- file manager
- go to your file system: grav-install-folder/user/themes/my-theme/css
- you will also probably want to check out the css file for the theme you're inheriting from
- you have two options

Option 1: copy the old theme's css file into your new theme, then make changes as you like
Option 2: create a new css file, and tell the partials/base.html.twig template (that everything extends) to use it, as well

- both of these options are pefectly fine
- for the tutorial we'll go through making a new file because if you know how to do that, option 1 should be perfectly easy, and it will be cleaner file-wise
- either way you will probably want to investigate the css used by the theme

Figuring out what to put in the css file:
- you will want to cover some of the basics of css from the W3Schools tutorial
- you don't have to be a pro, but you will need to understand some of the most basic syntax, etc.
- especially feel free to skip any sections modifying style aspects that you don't intend to modify - don't waste your time

- you will need to find out what classes, ids, and elements have styles applied to them that you want to change
- you also need to know what you want that style to be
- then it is a matter of combining them

- I recommend really just sticking to color, as that's quite simple
- once you get into "the box model" with margin and padding and such, that can get complicated and confusing
- all of this css stuff is on you to learn, though
- keep in mind, if you want to do something, google is your friend
- you may not find a helpful answer, or you may find that the thing is too complicated, but even if nothing comes of it you will have gained experience and knowledge
- don't just copy things that someone else wrote though - make sure you understand what you're copying first
- if you can't understand it, don't copy it - you don't know what unintended consequences it might have

To find out classes, ids, and elements have styles applied to them:
- use inspect element on your webpage
- hover over the lines of code until the area you are interested is highlighted
- use the little arrows to expand the code until you have pinpointed what you're looking for
- the box at the bottom shows all the styles that apply to this section - those that are crossed out have been overwritten by more important styles, so they don't matter very much

If the style you want to change is listed (let's say color):
- note whatever comes before the curly braces {} for that style aspect
- in your own css document, write that, add the curly braces, and add the style, just changing the color to what you want it to be
- color may be in several formats: rgb, rgba, hex codes, text

If the style you want to change is not listed:
- take a look at the code and see what classes, elements, or ids are used to reference it
- then use that for the selector and put your code inside the braces

I recommend using these methods for background colors, text colors, possibly font and font size. Of course, if you want to delve deeply into html and css, feel free to do whatever.