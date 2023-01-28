---
title: Self-referential how this Hexo thing works
---

## Daily use

Create a new .md file in `/source/_posts` and that will make a new post.

`npx hexo deploy -g` automatically generates and deploys using sftp.

## Setting up archive as homepage

1. Disable the index generator:
  `npm remove hexo-generator-index`

2. Change the archive path from `/archives` to `''`.

3. Override the "Keep on Posting" header: https://theme-next.js.org/docs/advanced-settings/custom-files.html#Hide-quot-Keep-on-posting-quot-in-Archive-Page

## Inspiration for replacement

This is an awful lot of code for something that I don't need to be this complex. I should probably just write my own, like [Evan did](https://neugierig.org/software/blog/2022/10/blog-software.html).