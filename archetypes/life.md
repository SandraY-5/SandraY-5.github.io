---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
tags: []
# --- Life 专属配置 ---
showToc: false      # 生活类通常不需要目录
comments: true
cover:
    image: ""       # 预留图片位置
    relative: true  # 开启相对路径
    alt: ""
---