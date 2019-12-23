---
title: Installation
taxonomy:
    category:
        - docs
visible: true
---

---
! Please note: This tutorial describes installing Grav using Reclaim Hosting, and specifically OU Create. If you are using this tutorial but wish to install Grav a different way, please refer to the [official documentation](https://learn.getgrav.org/16/basics/installation) for installation instructions.

## Set up your domain
If you are currently affiliated with OU, you have access to a free subdomain of oucreate.com through OU Create/Reclaim Hosting (or an inexpensive domain of your own). If you have not yet claimed this domain, please set it up now following the instructions [here](https://create.ou.edu/docs/getting-started/signing-up/).

## Install Grav
Once you have signed in to your dashboard on OU Create/Relcaim Hosting you will either see Grav listed under the Applications section or you can click on All Applications and find Grav from there. Click on Grav and then click on the "+ install this application" button. Most of the default settings for the installation are fine, but there are a few you may want to change.

#### Location
By default the installation will want to put Grav in a folder (directory) called cms. If you want Grav to be only one part of your domain then you should keep this folder but remain it to something more meaningful. Otherwise you can remove the folder by leaving the field blank. Essentially this will affect two things:
1. Your folder structure. Grav will be installed in either your home directory or in the folder specified.
2. The URL for your site. This URL will look something like `domain-name.oucreate.com`. If you install Grav in a folder, you will instead access it with the URL `domain-name.oucreate.com/name-of-folder`. 

#### Settings
You probably do not want to call your website _My cms_. You may also wish to provide your full name and to chek sure the email address, username, and password that are provided. These can be (almost) anything you like.

The only other setting you might want to change is the skeleton package. The default is GravCor + Admin which will give you a very basic Grav setup with the Quark theme and the Admin plugin (which provides the admin panel you will rely on) already installed. There are a few other options: Twenty, Resume, One Page, Photographer, Learn2 with Git Sync, Open Course Hub, Open MultiCourse Hub, and Open Publishing Space. Each of these provides a skeleton (some basic populated pages and possibly customized configuration options) along with a theme using the same name. If you check out these themes and decide that you love one of them, by all means go ahead and install it with Grav. If you install Grav with the default skeleton you can always add a skeleton later, but this will involve a bit more work.

## Finish
Once you are satisfied with your choices, click Install. Assuming a successful installation, you can now access your site.