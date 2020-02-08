---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
description: "Short book description"
tags:
- book
- russian
- english
---

** Новая прочитанная книга {{ .Name }} **
