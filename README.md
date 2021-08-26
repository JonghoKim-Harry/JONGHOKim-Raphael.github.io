JONGHO KIM's BLOG
======
## INTRODUCTION
This repository is using GitHub Pages to host JONGHO KIM's BLOG.  
See: https://pages.github.com/

## HOW TO WRITE A POST
You can write `.md` file in `_post` directory.  
The markdown file name should be `YYYY-mm-dd-TITLE` format.  
You can describe metadata in YAML format, then Jekyll will parse those metadata.  
Here is an example - `2020-09-29-NLP_language_model_trend.md`:  

``` Markdown
---
author_profile: true
title: NLP LANGUAGE MODEL TREND
layout: default
comments: true
category: NLP
tags: [AI, NLP, Language Model]
---
TITLE: Markdown document
===
## Introduction
### etc.
```



## HOW TO RUN LOCAL TEST
If you want to test locally, run:

```shell
nohup $(bundle exec jekyll serve) &
```
