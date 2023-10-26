---
title: "{{ replace (.Name | replaceRE "^[0-9]{2}-[0-9]{2}-[0-9]{4}-" "") "-" " " | title }}"
description: ""
type: post
tags: []
date: {{ .Date }}
slug: "{{ .Name | replaceRE "^[0-9]{2}-[0-9]{2}-[0-9]{4}-" "" }}"
---
