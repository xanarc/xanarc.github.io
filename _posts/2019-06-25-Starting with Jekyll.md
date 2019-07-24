---
title: Jekyll installation in Windows, easy and detailed 
layout: post
date: 2019-06-25 15:00
image: /assets/images/jekyllgithub.jpg
headerImage: true
tag:
- Jekyll
category: blog
author: xanamorris
description: Jekyll installation

---


# Jekyll Installation

## Let´s start with the installation then! 


To start, you´ll need to install Ruby + devkit (easy [executable](https://rubyinstaller.org/downloads/)). I´m chosing the last version at the moment, 2.6.3 -1. Accept the license, ok, install, when you press finish the command line will open and it will keep processing the installation, you only need to sit back and relax, in a few minutes it will be done! 
Next, Jekyll and Bundler, open the cmd and this is all:  

    gem install jekyll bundler

The installer will finalize and as the tutorial in Jekyll recommends: 

    jekyll -v
The cmd will retrive the version of Jekyll if it´s correctly installed. 
We´ll keep working with the cmd to create a new gemfile: 

    init bundle
As a result of this command you get a file called Gemfile in the specified (cmd) location. 
Edit that file, only by adding a line: 

    gem "jekyll"
Well, we are almost there... Now you might want to create a folder to save your jekyll projects. I´ve created my folder in documents, you can choose where it suits you better, and for obvious reasons, keep in mind the folder path. 
Last line, we run: `bundle exec jekyll new [folderpath]`

And Voila! 

Can you see there are folders and files created in your folder? Very good, welcome to Jekyll. 


