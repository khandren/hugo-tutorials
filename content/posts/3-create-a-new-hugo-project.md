---
title: "3. Create a new Hugo Project 🗳"
date: 2021-06-02T08:08:43+10:00
draft: false
---

{{< next-prev 
    prev-href="/posts/2.-install-hugo-mac" prev-text="2. Install Hugo on a Mac"
    next-href="/posts/4.-add-and-configure-a-theme" 
    next-text="4. Add and Configure a Theme"
    >}}

---

## Create a new Hugo Project

Create a folder called **Hugo** on the Desktop. This Hugo folder will contain the website we are about to make. Feel free to create this folder elsewhere.

- On Windows, right-click and do a 'Git Bash here' on your Desktop, or navigate to the folder using a command line.

pic

pic2

- For Mac, simply open up the Terminal app and navigate to your desktop `cd Desktop`.
- Then, enter the following commands:

```bash
hugo new site myWebsite
```

Feel free to change **myWebsite** to yourname-website, eg. john-website. This is essentially going to be the folder that holds everything that makes up a Hugo project.

`hugo new site myWebsite` creates a new Hugo project named **myWebsite**

A folder will be created with the website name you chose, already created with the main files that are needed for your website to work.

Inside your Hugo Folder, you will now see a new folder called `myWebsite`. Open it, and you will see that the skeleton or base of your website has been created:

pic3

{{< prev href="/posts/2.-install-hugo-windows" text="2. Install Hugo on a Windows">}}

{{< next-prev 
    prev-href="/posts/2.-install-hugo-mac" prev-text="2. Install Hugo on a Mac"
    next-href="/posts/4.-add-and-configure-a-theme" 
    next-text="4. Add and Configure a Theme"
    >}}