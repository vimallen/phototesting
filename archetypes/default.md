---
date: '{{ .Date }}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
categories: ["", ""]
tags: ["", ""]
cover:
  image: "/images/<file-name>"
  alt: "<alt text>"
  caption: "Caption here"
  relative: false # To use relative path for cover image, used in hugo Page-bundles
---
