# SOAR Website

[![Build Status](https://travis-ci.org/grant0417/usfsoar.github.io.svg?branch=master)](https://travis-ci.org/grant0417/usfsoar.github.io)

This is SOAR's new website, which is planned to make its public debut in Fall of 2020. The site will eventually be live at usfsoar.com.

[View Site](https://usfsoar.github.io)

## Contributing

### Using GitHub

The easiest way to contribute is simply by using the GitHub website. Create a
GitHub account and click the "Fork" button on the top right of this page to fork
the repository to your account. Then you can edit any page by clicking the
pencil icon after clicking on any file in the `content` folder. Include images
and other files by uploading them to the correct subfolder in the `static`
folder and link to them in the page.

For a quick introduction to editing markdown files, see this
[cheatsheet](https://www.markdownguide.org/cheat-sheet/).

Once you are done editing your file, add a descriptive commit message and commit
the changes. Then, submit a pull request and an officer will review your
changes.

### Using a Code Editor

If you prefer to use a local code editor to edit the website, you can do that
too! Simply fork the repository, clone the fork to your machine, make your
changes, commit and submit a pull request.

If you want to preview your changes before submitting a request, you can run the
site on your local machine:

### How to develop the site locally

1. Clone the site using GitHub or pull most recent commit

```
git clone url
git pull
```

2. Make changes to site

3. Test changes using [Zola](https://www.getzola.org/)

```
zola serve
```

4. If changes serve and are correct add any new files and commit back to the main branch

```
git add file1 file2
git commit -a -m "Description of change"
git push
```

### How to add a web page

1. Create a file in the `content` folder titled what you want your page's url to be with a description of `.md`

2. Add to the top of the page (the description is optional)

```
+++
title="Title"
description="A longer description"
+++
```

3. Type the rest of the page in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### How to add a blog post

1. Create a file in the `/content/blog/` folder titled what you want your blog post's page's url to be with the extension of `.md`

2. Add to the top of the page 

```
+++
title="Title"
date=yyyy-mm-dd
+++
```

3. Type the rest of the page in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

### More advanced changes

If you want to make more advanced changes please contact Grant <grant0417> for help if you don't know what you are doing or making big changes.
