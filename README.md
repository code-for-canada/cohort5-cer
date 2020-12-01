# Cohort 5 CER Fellows Website

This is the code for the GitHub Pages blog where the cohort 5 Fellows at the CER will post informal updates and various other stuff.

## Adding Posts

To create new posts, add files with names in the form of yyyy-mm-dd-title.md to the _posts directory with the date corresponding to the post date and "title" replaced by the title of the post but lowercase and with dashes instead of spaces (e.g. "hello-world" instead of "Hello World"). The content of posts uses [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

The beginning of the post file should contain Jekyll front matter between triple dashes, such as the following:
```YAML
---
layout: post
title: Hello World
categories:
- General
feature_image: "https://www.example.com/myphoto"
---
```
Replace the title, categories, and feature image appropriately.

## Questions

Feel free to reach out to Ian for clarification.

## Theme Info

The Jekyll theme used for this site is [Alembic](https://alembic.darn.es/) with some customizations.
