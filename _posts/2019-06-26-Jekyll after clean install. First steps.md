---
title: Jekyll installation	
layout: post
date: 2019-06-26 12:00
image: /assets/images/jekyll-logo-light-solid.png
headerImage: true
tag:
- Jekyll
category: blog
author: xanamorris
description: Jekyll installation detailed guide
---

### Jekyll after clean installation first steps and how to set up a template.

To recap, we left it after Jekyll was installed. 
We'll continue using the cmd. And to start we can change the directory to the folder path which we assigned to our project. 

Jekyll docs have a list of useful commands to handle tasks throught the cmd, please find it [here](https://jekyllrb.com/docs/usage/)

Run cd + folderpath command. 
We try to build the page, to see how our starting point looks like. 

    cd [folderpath] 
    bundle exec jekyll serve
And I get an error! **Could not find gem 'minima (~> 2.0) x64-mingw32' in any of the gem sources listed in your Gemfile. Run* `bundle install` to install missing gems.*

When I try again to browse 127.0.0.1:4000, a basic page with a basic header and footer and in the center the section posts. Very exciting times. 

I think then now it makes sense to try to make sense of what´s all those files and folders. And I´ll start by the most important file, which it is: _config.yml 

As we opened the file we'll see a warm Welcome to Jekyll, and then a number of settings ready to be set up. Official link [here](https://jekyllrb.com/docs/configuration/) for the configuration is very well explained. 

I would recommend to browse Jekyll templates and pick up your favourite, there are tons, and some adjusts better than others depending on the type of site, content you want to offer, etc. 

The template I chose is this one: [http://koppl.in/indigo/](http://koppl.in/indigo/)

Css is very time consuming, and not my main interest. Therefore I found that the biggest advantage of using a template is that it will help me to gain time for other aspects or skills I want to improve. 
I chose my template due to cleanness, basic design. It highlights posts and developer profile, and it doesn´t force me to upload pictures. It does look great, doesn´t it? And I made a couple of changes to adjust the menu to my likes, I've designed my coco icon and a few things more, apart from customize the site to make it mine. 



A few concepts related with Jekyll: 

As the YAML page claims:
[YAML](https://yaml.org/) - Ain't Markup Language, YAML is a human friendly data serialization standard for all programming languages. 

**Serialization is** the process of converting an object into a stream of bytes to store the object or transmit it to memory, a database, or a file. Its main purpose **is** to save the state of an object in order to be able to recreate it when needed. 

Gem, gemfiles, bundler: 

Bundler is a gemfile manager. Gems are called in gemfiles. And what's a gemfile? 

> [A Gemfile is a file we create which is used for describing gem dependencies for Ruby programs. A gem is a collection of Ruby code that we can extract into a “collection” which we can call later.](https://tosbourn.com/what-is-the-gemfile/)

Jekyll is a gem itself, do you remember we added the gem in the installation post? 

This gems provides functionality through plugins and pairs this functionality along the different users. The way we storage our gems is by include them in the gemfile. And all this process is managed by Bundler. 

> [Using Gemfiles and the bundler makes dealing with different versions of plugins much easier and ensures we can have a consistent environment for our site across multiple machines.](https://learn.cloudcannon.com/jekyll/gemfiles-and-the-bundler/)
> 
> 
There is a entire world of new concepts in every step of the way. I'll try to stick definitions (and of course the source). 
> Written with [StackEdit](https://stackedit.io/).

