---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
author: Mad Man
year: "{{ dateFormat "2006" .Date }}"
month: "{{ dateFormat "2006/01" .Date }}"
categories:
- Personal
- Thoughts
tags:
- software
- html
---

This is the enticing bit that people will see in the summary.

<!--more-->

This stuff is the rest of the article.
