# Nathan's ePortfolio (Jekyll)

This repository contains the configuration and structure for my **personal ePortfolio**, built with **Jekyll** and hosted on **GitHub Pages**. It showcases my background, projects, and skills in **Computer Science**.

---

## ⚙️ Overview

The main configuration file is **`_config.yml`**, which defines your site’s title, navigation, theme, and metadata.  
This setup includes all required sections for the portfolio:

- **Welcome Page** – brief introduction and purpose  
- **About** – personal background, goals, and education  
- **Contact** – ways to reach me  
- **Experience** – professional, academic, or project-based experience  
- **Projects** – highlights of my GitHub repositories with descriptions and links  
- **Skills** – list of tools, languages, and frameworks  
- *(Optional)* **Resume** – downloadable PDF or embedded document  

---

## 🧩 Example `_config.yml`

```yml
title: "Nathan's ePortfolio"
description: "A showcase of my computer science projects, experience, and skills."
baseurl: "" # leave blank for GitHub Pages user site
url: "https://<your-github-username>.github.io"
author:
  name: "Nathan"
  email: "your.email@example.com"

theme: minima

# Navigation
header_pages:
  - index.md        # Welcome Page
  - about.md
  - experience.md
  - projects.md
  - contact.md
  - skills.md
  # - resume.md     # Optional

# Social Links
social_links:
  github: <your-github-username>
  linkedin: <your-linkedin-username>

# Footer
show_excerpts: true
