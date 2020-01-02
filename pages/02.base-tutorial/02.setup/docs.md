---
title: Setup
taxonomy:
    category:
        - docs
visible: true
---

---

! Please note: This tutorial describes installing Grav using Reclaim Hosting, specifically through OU Create. If you are using this tutorial but wish to install Grav a different way, please refer to the [official documentation](https://learn.getgrav.org/16/basics/installation) for installation instructions.

## Set up your domain

If you are currently affiliated with OU, you have access to a free subdomain of oucreate.com through OU Create/Reclaim Hosting (or an inexpensive domain of your own). If you have not yet claimed this domain, please set it up now following the instructions [here](https://create.ou.edu/docs/getting-started/signing-up/).

## Install Grav

Once you have signed in to your dashboard on OU Create/Relcaim Hosting you will either see Grav listed under the Applications section or you can click on All Applications and find Grav from there.

- Show screenshots of Grav/installation -

While most of the default settings for the installation are fine, there are a few we want to change.

By default, the installation will want to put Grav in a folder (directory) called cms. You can choose instead to install Grav directly in your home folder by leaving the field blank, or you can change the name of the folder. If you leave the folder blank, the URL to your website will be `NOCLIP domain-name.oucreate.com`. If you install Grav in a folder, the URL will instead by <code>NOCLIP domain-name.oucreate.com/name-of-folder</code>. For this tutorial, we will name our folder grav.

- screenshots -

We also need to set the website name, as well as our full name, email address, username, and password, as shown here.

- screenshot - 

Finally, the only other setting we might consider changing here is the skeleton package. The default, GravCor + Admin, is not bad, but depending on what we want to do, a skeleton package might make setting up the website easier. For this tutorial we will stick with the default, but you can get more information in the mini tutorial on skeletons.

- screenshot?, link -

All we need to do now is press install.

## Check out the admin panel

Familiarity with the admin panel is important, as this is where we will spend most of our time building our website. You can access the panel by going to `NOCLIP your-website-url/admin`. You will be directed to log in using the username and password you chose when installing Grav.

- screenshots -

!!! The Grav documentation has a whole chapter dedicated to the [administration panel](https://learn.getgrav.org/16/admin-panel). It is worth skimming, at the very least.

Before choosing a theme and creating content you should make sure that Grav is up-to-date. Most likely you will need to update plugins and Grav itself. There should be a button on the dashboard to check for updates, but if you have any issues you can check the [documentation](https://learn.getgrav.org/16/admin-panel/dashboard).

- walk through updating
- screenshots