---
title: 'Finishing Touches'
taxonomy:
    category:
        - docs
visible: true
---

---

We have several modules added to our modular homepage, but there are a few things to do before we can truly call it done.

## Navigation

As with the [one-page site example](https://demo.getgrav.org/onepage-skeleton/), the navigation bar at the top of the site references the modular pages we have added, rather than the rest of the website's pages. On top of that, the names we gave those pages look rather odd as navigation options.

- screenshot

We can start by changing how the pages appear on the navigation menu. This is easily done in the page editor on the Advanced tab. I would like the header to be referred to as "Top" in the navigation bar, but I really don't want to change the title of the page to Top. Setting the _Menu_ field to Top allows me to do this.

- screenshot

After changing the Menu fields of the other pages, the navigation bar looks like this.

- screenshot

That's very nice and all, but this is not a one-page website. It would be more helpful for the navigation bar to help navigate the rest of the site. To do this we can go to the modular page (Home) and switch the editor to expert mode. In the frontmatter, we than have to type:

```yaml
onpage_menu: false
```

That is all it takes. The navigation bar should now look how we want it.

- screenshot

## Classes

If you recall, when we created the header hero for the blog page we had to change the text color so it would show up. We did this by adding a class to the hero classes. There are other options for adding classes to modify the look and feel of our site. There are two places we can do this: On the Advanced tab in Body Classes, and on the Hero tab in Hero Classes. It is worth doing some experimenting so you can see what your options are.

- choose a few classes to showcase

- anything else?