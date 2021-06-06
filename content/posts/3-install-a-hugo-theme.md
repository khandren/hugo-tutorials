---
title: "3. Install and Configure a Hugo Theme 🎨"
date: 2021-06-02T07:06:16+10:00
draft: false
---

## Using a Hugo Theme

There are so many [Hugo themes](https://themes.gohugo.io/) to choose from and they have slightly different ways to set it up depending on the one you pick. Most come with instructions on how to set them up, so be sure to check that they have setup instructions.

In this tutorial, we will use the [Mini theme](https://themes.gohugo.io/hugo-theme-cactus-plus/) for our Hugo site. 

To install the Mini theme into your Hugo project, enter the following commands in your Command Line / Terminal:

```bash
cd myWebsite
git init
git submodule add https://github.com/nodejh/hugo-theme-mini.git themes/mini
```

> **git init** - Initializes your myWebsite folder into a git repository. This means you will be able to store your code  on GitHub.

Open your `myWebsite` folder on your computer, navigate to `themes/mini/exampleSite`.

![Alt Text](https://github.com/khandren/hugo-tutorials/blob/blog/static/images/3/miniThemes.gif?raw=true)

Copy the content, layouts, static and config.yaml files into your `myWebsite` folder.

![Alt Text](https://github.com/khandren/hugo-tutorials/blob/blog/static/images/3/copyContentsLayoutsStaticConfig.gif?raw=true)

Copy this file (link to download the `netlify.toml` file) and place it into your `myWebsite` folder.

Link to download

Delete the `config.toml` file in your `myWebsite` folder because the `config.yaml` file should replace it.

We need to make some adjustments to the `config.yaml` file for the theme to work. 

Open `config.yaml` using a text editor (such as Atom, Notepad++, or VS Code).

Delete lines 6 and 7 and change `theme: hugo-theme-mini` to `theme: mini`.

{gif}

Save the file.

Finally run `hugo serve` on your Command Line or terminal. 

Then on your favorite browser, go to localhost:1313. You should see the theme is installed and already has content!
