---
title: Requirements
taxonomy:
    category: docs
meta:
    layout: layout
---


## Requirements 

CSYCMS is intentionally designed with few requirements. You can easily run CSYCMS on your local computer, as well on all nodejs Web hosting providers. If you have a pen handy, jot down the following CSYCMS system requirements:

1. Web Server (Apache, Nginx, etc.)
2. Nodejs v 8.x or higher

CSYCMS is built with plain text files for your content. There is no database needed. In fact you can copy your content from grav and use them here.

## Web Servers

CSYCMS is so simple and versatile that you don't even need a web server to run it. Its written in node and you can serve it directly. You will only need a webserver to profixy your own nodejs server, to get it running on PORT 80 of a registered domain.

Even though technically you do not need a standalone web server, it is better to run one, even for local development. There are many great options available:

### Mac

* OS X 10.13 High Sierra already ships with the Apache Web server.
* [MAMP/MAMP Pro](http://mamp.info) comes with Apache. 
* [AMPPS](http://www.ampps.com/downloads) is a software stack from Softaculous enabling Apache, PHP, Perl, Python,..

You will have to check for yourself how to set the configurations you need.

### Windows

We have not tested on Windows yet

### Linux

* Many distributions of Linux already come with Apache. If they're not, the distribution usually provides a package manager through which you can install them without much hassle. More advanced configurations should be investigated with the help of a good search engine.
* Nginx. This is the server we would recommend as it utilizes system resources more efficiently than apache.

## Nodejs
You will require to set up nodejs to run csycms. Please [check this page](https://joshtronic.com/2018/05/07/how-to-install-the-latest-version-of-nodejs-8-on-ubuntu-1804-lts/) for how to do this in linux.

## Server configuration
If you are using an Ubuntu 16.04 server (or any other), then you may need to check that you have killall working. Otherwise CSYCMS will not be able to content the auto-update scripts. If it is not, then you can check for how to [fix killall-command-not-found](https://bytefreaks.net/gnulinux/bash/bash-killall-command-not-found-a-solution)

## SSH Keys
If you use a private repo for your site content, then you will need to set-up the ssh keys for accessing the private repo. [See how you can create one](https://confluence.atlassian.com/bitbucket/set-up-an-ssh-key-728138079.html)

## Recommended Tools

### Text Editors

Although you can get away with Notepad, Textedit, Vi, or whatever default text editor comes with your platform, we recommend using a good text editor with syntax highlighting to make things easier. Here are some recommended options:

1. [SublimeText](http://www.sublimetext.com/) - OS X/Windows/Linux - A commercial developer's editor, but well worth the price. Very powerful especially combined with plugins such as [Markdown Extended](https://sublime.wbond.net/packages/Markdown%20Extended), [Pretty YAML](https://sublime.wbond.net/packages/Pretty%20YAML), and [PHP-Twig](https://sublime.wbond.net/packages/PHP-Twig).
2. [Atom](http://atom.io) - OS X/Windows/Linux - A new editor developed by Github. It's free and open source. It is similar to Sublime, but does not have the sheer depth of plugins available yet.
3. [Notepad++](http://notepad-plus-plus.org/) - Windows - A free and very popular developer's editor for Windows.
4. [Bluefish](http://bluefish.openoffice.nl/index.html) - OS X/Windows/Linux - A free, open source text editor geared towards programmers and web developers.
5. [Visual Studio Code](https://code.visualstudio.com/) - A lightweight but powerful source code editor which runs on your desktop and is available for Windows, macOS and Linux.

### Markdown Editors

Another option if you primarily work with just creating content, is to use a **Markdown Editor**. These often are very content-centric and usually provide a **live-preview** of your content rendered as HTML. There are literally hundreds of these, but some good options include:

1. [MacDown](http://macdown.uranusjr.com/) - OS X - Free, a simple, lightweight open source Markdown editor.
2. [LightPaper](http://lightpaper.42squares.in/) - OS X - $9.99, clean, powerful. Our markdown editor of choice on the Mac. **Get 25% OFF with Discount Code: GET_CSYCMS_25**
3. [MarkDrop](http://culturezoo.com/markdrop/) - OS X - $5, but super clean and Droplr support built-in.
4. [MarkdownPad](http://markdownpad.com/) - Windows - Free and Pro versions. Even has YAML front-matter support. An excellent solution for Windows users.
5. [Mark Text](https://marktext.github.io/website/) - Free, open source Markdown editor for Windows / Linux / OS X. 
