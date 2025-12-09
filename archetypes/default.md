---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
tags: []
categories: []

# --- 页面功能开关 ---
showToc: true       # 默认开启目录 (写技术文方便)
TocOpen: true       # 默认展开目录
comments: true      # 默认开启评论

# --- 封面图设置 (生活文专用) ---
cover:
    image: ""
    relative: true
    alt: ""
---