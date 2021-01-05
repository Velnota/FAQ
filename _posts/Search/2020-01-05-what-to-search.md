---
layout: post
title: "What can I search?"
date: 2021-01-05
category: search
author: Velnota
short-description: The Content You'll See in Search
---

-----

By default Odin uses two Google Fonts, Muli and Poppins. To change these font choices, first navigate to `_scss/_variables` and find the Google Font import on line 1.

Replace this import with the Google Font(s) of your choice and then find the Fonts section of the variable file (starts on line 50). Make sure to update these to use your chosen fonts, primarily **$base-font-family** and **$header-font-family**.

After editing your fonts, run jekyll serve to see the changes locally. If you’re satisfied with your changes, run jekyll build and then push your changes to your repo.

