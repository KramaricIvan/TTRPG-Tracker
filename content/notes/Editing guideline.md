---
title: "Editing guideline"
enableToc: true
---

# 1. Metadata

## 1.1 Titles

- Quartz requres precise title metadata
- so if you are ever making a new page, it has to have a metadata element which you can make by encapsualting text metadata with --- --- 
- first key in metadata must be "title:"
- value in "title:" key must be in double qoutes " "

## 1.2 YAML

- metadata is based on YAML 
- YAML is lowkey a standard in technical documentation today 
- it has a fun recursive name YAML stands for YAML ain't a markup language
- so yeah, if you want to make some tag system or expand the vault a lot, try to stick to YAML syntax

# 2. Images

- Sort images you add to coresponding folders
- If it's something for the campaign pages, then sort it in that campaigns image folder
- if it's something for the notes and guides, then sort it in the notes/images folder

# 3. CSS

- you can add custom CSS styling and change existing colours through editing `assets/styles/custom.scss`. If you'd like to target specific parts of the site, you can add ids and classes to the HTML partials in `/layouts/partials`. 