---
title: Setup
taxonomy:
    category:
        - docs
visible: true
---

---
## Installation

! Please note: This tutorial describes installing Grav using Reclaim Hosting, and specifically OU Create. If you are using this tutorial but wish to install Grav a different way, please refer to the [official documentation](https://learn.getgrav.org/16/basics/installation) for installation instructions.

### Set up your domain
If you are currently affiliated with OU, you have access to a free subdomain of oucreate.com through OU Create/Reclaim Hosting (or an inexpensive domain of your own). If you have not yet claimed this domain, please set it up now following the instructions [here](https://create.ou.edu/docs/getting-started/signing-up/).

### Install Grav
Once you have signed in to your dashboard on OU Create/Relcaim Hosting you will either see Grav listed under the Applications section or you can click on All Applications and find Grav from there. While most of the default settings for the installation are fine, there are a few you may want to change.

By default the installation will want to put Grav in a folder (directory) called cms. You can choose instead to install Grav directly in your home folder by leaving the field blank, or you can change the name of the folder. If you leave the folder blank, the URL to your website will be `NOCLIP domain-name.oucreate.com`. If you insall Grav in a folder, the URL will instead by <code>NOCLIP domain-name.oucreate.com/name-of-folder</code>.

You will also set your website name, full name, email address, username, and password. The only other setting you might want to change is the skeleton package. The default, GravCor + Admin, is not bad, but it is worth briefly checking out the demo websites listed below. If you know you want to use a theme/setup like one of them, choosing that package when installing Grav will make setting up your website easier.

Links to demo websites:
* [Twenty](https://demo.getgrav.org/twenty-skeleton/)
* [Resume](https://demo.getgrav.org/resume-skeleton/)
* [One Page](https://demo.getgrav.org/onepage-skeleton/)
* [Photographer](https://demo.getgrav.org/photographer-skeleton/)
* [Learn2 with Git Sync](https://demo.hibbittsdesign.org/grav-learn2-git-sync/)
* [Open Course Hub](https://demo.hibbittsdesign.org/grav-open-matter-course-hub/)
* [Open MultiCourse Hub](https://demo.hibbittsdesign.org/grav-skeleton-open-matter-multi-course-hub-site/)
* [Open Publishing Space](http://demo.hibbittsdesign.org/grav-open-publishing-quark/)

These are not the only options available, so if none of them appeal, don't worry about it and just install the default package.

## The Admin Panel
Familiarity with the admin panel is important, as this is where you will spend most of your time building your website. You can access the panel by going to `NOCLIP your-website-url/admin`. You will be directed to log in using the username and password you chose when installing Grav.

!!! The Grav documentation has a whole chapter dedicated to the [administration panel](https://learn.getgrav.org/16/admin-panel). It is worth skimming, at the very least.

Before choosing a theme and creating content you should make sure that Grav is up-to-date. Most likely you will need to update plugins and Grav itself. There should be a button on the dashboard to check for updates, but if you have any issues you can check the [documentation](https://learn.getgrav.org/16/admin-panel/dashboard).