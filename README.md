# website
Hexo files for our website at https://ugobc.ca

## Contributing
To contribute to the content of this website you will need [git](https://git-scm.com/downloads) and [Node](https://nodejs.org/en/). You will also need an editor, I personally use VSCode but any editor will work. For help feel free to contact theGordHoard#9607 on Discord.

### Getting Started
Clone this repo and run `npm install` in it. You will also need to run `npm install -g hexo-cli` to install the Hexo command line tools.

### Creating a new Post
To create a new post, open a terminal and navigate to this repo. Run `hexo new post <name>` where `name` is the name of the post. A new file will have been created in `source/_posts`. Edit the metadata to your needs, making sure to include the author field with your Discord username and Discriminator. For example:

```yaml
---
title: Hello World
date: 2018-06-27 08:57:06
tags:
- hello
- world
- meta
author: theGordHoard#9607
---
```

After you fill the metadata in you are free to write the rest of your post. Below the `---` you can write using full featured markdown. If you want to save your changes but don't want them to be live on the site, move the file to the `_drafts` folder.

### Creating a new Page
Creating a new is much like creating a new Post, the command has one difference: `hexo new page <name>`. Keep in mind that tags do not work on pages.

### Previewing Changes
To preview your changes run `hexo server` in the root of the repo. Go to the URL

### Pushing Changes
Commit your changes with a descriptive message and push them, then let Gord know so he can deploy them.