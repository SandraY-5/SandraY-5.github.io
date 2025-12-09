---
title: 网页的更新记录
date: 2025-12-09
draft: false
showToc: true
TocOpen: true
tags:
  - Machine Learning
  - Tech
---


网站是基于Hugo搭建，底层是github，目前是个public的

## 功能
#### 板块：
目前是Lab和Life两个板块，Lab想要用来记录一些技术类，学术类的内容；Life板块，想要记录一些兴趣爱好类的内容
#### 功能
- 板块分类
- Tag查询
- 全局Search
- Archive：文章timeline排序 （按照什么timeline排序？新建，还是编辑？）
- 文章内评论功能：基于_[giscus](https://giscus.app/) （后续需要了解一下，评论数据存放在什么地方了）

## 后续想要优化的内容
- [ ] 目录移到侧面
- [ ] words count only count based on English words? What if I want count all the English and Chinese words?




-------

## 网站建立的笔记
- 目前网站配色：
``` css
:root {
/* 链接和高亮色：深墨绿 */
--primary: #5f624e;
/* 鼠标悬停时的颜色：浅一点的绿 */
--secondary: #b7b397;
}

```
- 按照预设的template新建文章：hugo new life/test-final/index.md
	- life和tech的预设是不同的
	- template的名字，会是Test Final


### 日常文章发布步骤
1. 在 terminal 新建template ： hugo new tech/英文文件名/index.md
2. 在obsidian撰写文章，每个文章都有一个文件夹，在index.md中编写
3. 用terminal发布到git：
```bash
git add .
git commit -m "update blog"  # 引号里随便写
git push
```


