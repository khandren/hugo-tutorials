---
title: "3. Create a new Hugo Project 🗳"
date: 2021-06-02T08:08:43+10:00
draft: false
---

## Setup where you will create the project

**Using Windows**

- You can navigate to your desktop using the command line. Run the command:
  ```bash
  cd Desktop
  ```
  
{{< centered-img src="/images/3/cmd.PNG" title="homebrew" alt="homebrew">}}

- Create a folder and right-click on the folder. Click on 'Git Bash here'. This will open a bash command line.
  
{{< centered-img src="/images/3/bash.png" title="homebrew" alt="homebrew">}}

**Using MAC**
- Simply open up the Terminal app and navigate to your desktop using the command `cd Desktop`.
  ```bash
  cd Desktop
  ```

## Create a new Hugo Project

- Enter the following command:

```bash
hugo new site myWebsite
```

`hugo new site myWebsite` creates a new Hugo project named **myWebsite**

> Feel free to change **myWebsite** to yourname-website, eg. john-website. This is essentially going to be the folder that holds everything that makes up a Hugo project.

A folder will be created with the website name you chose (for example, `myWebsite`). It will be created with the main files that are needed for your website to work. If you open it, and you will see that the skeleton or base of your website will already be there:

{{< centered-img src="/images/3/base.png" title="homebrew" alt="homebrew">}}
