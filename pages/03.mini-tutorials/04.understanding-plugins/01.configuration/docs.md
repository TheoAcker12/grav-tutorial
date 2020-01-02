---
title: Configuration
taxonomy:
    category:
        - docs
visible: true
---

---

Email configuration as an example

Configuring Email Plugin
-	You need to configure this if you want to receive emails directly from the website.
-	Set mail engine to SMTP
-	Provide from and to addresses and names 
-	Make sure your SMTP login name and password match your OU Create login and password
-	Beyond that, I wouldn’t fiddle with the defaults. The default body might look a little messy, but you’ll have to decide if it’s annoying enough to fiddle with html or pointing to the right template

OR

#### Configuring the email plugin
If you want to receive emails directly from your website by using a contact form then you need to set up this plugin with the correct information. The email plugin does have a very useful Readme, but you may find it a bit heavy on the code. For now, all you need to worry about is filling out the correct fields in the plugin configuration.
1. Mail Engine: SMTP
2. From address: When you receive mail, this is the address that will be shown to have sent it. Some emails may require a little bit more set up. For example, if you wish to use a gmail address, the plugin's Readme can tell you what you need to do.
3. From name: Optional, but I like to put something that tells me the email is coming from my website.
4. To address: The email address you want any emails sent to.
5. To name: Again, optional, but you probably want to put your own name.
6. SMTP information should be already filled out for you. Double check that the name and password are the username and password for your Reclaim Hosting/OU Create account. Grav will automatically want to user the username and password for your Grav website, which may be different.
7. Beyond that, I would not recommend fiddling too much with the defaults. You can always experiment later.
