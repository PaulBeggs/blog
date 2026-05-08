---
layout: post
categories: misc
author:
- Paul Beggs
comments: true
---

## Overview

In Lab 8 of CSCI 340, we were tasked with completing a Razor Page tutorial, and then creating our own project, using what we learned from the tutorial. [This link](https://github.com/PaulBeggs/csci340lab8) will take you to my GitHub repository for my Razor Page project.

## The Tutorial

The tutorial consisted of 9 steps, and each step required copy and pasting from the tutorial into the directory, or running some dotnet commands in the CLI. I never really understood what model binding does during the tutorial (i.e., the `[BindProperty]` tag), but I later found out that it's how we assign values to properties from the webpage to the database. In terms of what was easiest about the tutorial, I think adding the `[Display(Name = ...)]` attributes were straightforward, and made intuitive sense. The hardest part was keeping track of the files that they wanted me to edit, as the naming convention was a bit hard to understand at first, and the nested folders made the directory into a maze.

## My Application

Transitioning from the tutorial to my own application was pretty tricky, as I couldn't just copy and paste anymore. That is, since I changed the name of my project, and the folder names, I had to pay attention to the namespaces and the code generating commands in the CLI. It didn't help that since I use Bash in my terminal, that I would mistakenly use the Window's command, but it would be displayed wrong. It took me a little too long to fix this problem. Other than that, I thought that the documentation from the tutorial was good, so it was easy to make the changes that I wanted on my application.

In terms of parallels between Razor Pages and Jekyll, there are a lot. To put it in terms of coding languages, Jekyll feels more like Python, and Razor feels like Java, but on steroids. With that being said, I think this dichotomy has many pros and cons. Like, with Razor Pages, there are a ton more customizations you can make, and you can literally build anything you want on the website. Jekyll feels more constricting with less features overall. With that said, you can get a Jekyll blog website, and subsequent blogs up in no time, which starkly contrasts Razor Pages.

Even though this blog is late, I do remember how I felt about making another Razor application, and it was generally neutral. I can be slow to get started on applications, and it can be difficult to track how a database is updated and modified via CRUD operations through the website. 