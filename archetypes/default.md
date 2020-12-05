---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
url: {{md5 .File.TranslationBaseName}}
---

