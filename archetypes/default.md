---
post: {{ len (where .Site.Pages "Section" "==" "blog") }}
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
tags: []
slug: {{ .File }}
draft: false
---

