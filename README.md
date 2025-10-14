# Nathan's ePortfolio (Jekyll)

This repository contains the configuration and structure for my personal ePortfolio, built with Jekyll and hosted on GitHub Pages. It includes pages for my background, experience, projects, and skills in Computer Science.

## ⚙️ Overview

The main configuration file is `_config.yml`, which defines the site’s title, navigation, theme, and metadata.  
This setup includes:

- Welcome Page  
- About  
- Contact  
- Experience  
- Projects  
- Skills (tools, languages, frameworks)  
- Optional Resume  

## 🧩 `_config.yml`

```yml
title: ""
description: ""
baseurl: ""
url: ""
author:
  name: ""
  email: ""

theme: minima

header_pages:
  - index.md
  - about.md
  - experience.md
  - projects.md
  - contact.md
  - skills.md
  # - resume.md

social_links:
  github: ""
  linkedin: ""

show_excerpts: true
