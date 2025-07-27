+++
# 基本信息
date = '2025-07-26T21:14:04+08:00'
title = 'hello world'
author = 'jimson'
# 文章标签和分类
tags = ['博客', 'Hugo']
categories = ['文章', '分享']
# 文章摘要（首页卡片上显示）
summary = '这是我 Hugo 博客的第一篇文章'
# 是否草稿（本地用 hugo server -D 才能看到）
draft = false
# 是否置顶（首页优先显示）
weight = 1
# 是否隐藏发布日期、阅读时间等信息
hideMeta = false
# 封面图（显示在首页卡片）,这个图片放到 static/images/background.jpg
# 需要注意的是[cover]标签需要放在最后面，不然会影响页面布局，例如将[cover]标签放在weight前面和后面效果是不一样的
[cover]
    image = "images/background.jpg"   # 图片路径
    alt = "封面图"                  # 备用文字
    caption = "这是一张封面图"       # 说明
    relative = true                 # 是否相对路径
+++
