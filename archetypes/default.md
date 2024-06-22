---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
lastmod: {{ .Date }}
draft: false # 是否为草稿
author: ["kangi"]

summary: "" # 首頁顯示的文字總結段落

categories: 
- 技術
- 閱讀
- 生活
tags: # 自由新增
- 
- 

description: "" #敘述
weight: # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
slug: ""

isCJKLanguage: true # 是否是中文(chinese,japanese,korea) 字數判斷用
comments: true
showToc: true # 顯示目錄
TocOpen: true # 預設打開目錄
hidemeta: false # 是否隱藏meta訊息(ex:發布日期、作者...etc)
disableShare: false # 取消社群分享區塊
showbreadcrumbs: true # 於頂部顯示文章路徑
ShowWordCounts: true
ShowReadingTime: true
ShowLastMod: true

cover:
    image: "" # 封面圖片路徑 (ex:clear-301-redirection-cache-chrome/cover.jpg)
    caption: "" # 封面圖片下方描述
    alt: ""
    relative: false
---
