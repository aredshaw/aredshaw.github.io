---
title: "Hugo - What it is, and how to use it"
date: 2019-11-15T10:38:45-08:00
draft: true
---
# Working with Hugo

*<<This page can be viewed as a [website](https://aredshaw.github.io), or a [GitHub README](https://github.com/aredshaw/aredshaw.github.io).>>*

Hugo is one of the fastest **static site generators** available. It is also one of
the most popular. Here are some basic instructions for setting it up on Linux.

*For documentation from the source, see
[Hugo docs](https://gohugo.io/documentation/).*

To get started, follow these simple steps:

1. Download and install Hugo on your system. For Linux, from the
   command-line, type `sudo apt-get install hugo`.
2. Create a new site. `hugo new site HugoSite`.
 * Note: The name "HugoSite" will be the directory where your site is located. Make
  the name whatever you want it to be. You could use `hugo new site MySite` or
  something like that.

3. Write something. To create a doc, first get inside your site (ex. HugoSite). From command-line, type `hugo new
   index.md`.
 * You could also create pages such as index.html, posts/my-first-page.md, etc.
    There are a lot of options here, so consult the official documentation for
    more.

4. Add whatever content you want. The page you just created (my-first-page.md,
   index.html, etc.) can be edited using whatever text editor you want.

5. Set up the server. In the command-line, type `hugo server -D`. The server
   will continuously update the page (http://localhost:1313/ by default) or any
   other content you change. You can stop the server using `ctrl-c`.

On a practical note, sometimes I had to save my document more than once while the
server was running. At times after a save, a blank or default document showed up
on the website. To remedy this, all I had to do was save the document again, and
the text showed up on my screen.

Additionally, you can install a great [many themes](https://themes.gohugo.io/) for Hugo.

Have fun!
