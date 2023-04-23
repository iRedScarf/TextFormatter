# TextFormatter
1. 这是GPT-4.0的作品。
2. 下面是我请它帮忙时跟它说的：
'
请帮我写一个简单的程序，功能是能自动把一篇政府颁布的规章制度的文本编辑成我要的html格式，要求如下：
1. 章节标题使用h4标题、黑体字、在页面居中，例如'第一章 总则'自动变成'<h4 style="text-align: center; font-family: 'SimHei', sans-serif;">第一章 总则</h4>'。
2. 条款段落使用默认正文字体大小，但其中的'第x条'需要用黑体字加粗显示，并且每个自然段落都需要在第一个字前空两个全角空格，例如'第一条 为加强我区政府投资项目管理……'自动变成'<strong style="font-family: 'SimHei', sans-serif;">　　第一条　</strong>为加强我区政府投资项目管理……'。
3. 最好能有一个简单的前端页面，包含一个输入窗口（用于输入原始文本）和一个输出窗口（输出编辑好格式的文本）。
4. 最好能在上面的前端页面中添加文本的标题（title）、子标题（subtitle）、标签（tags）、作者（author）、日期（date）等信息，在输出的文本的最前端以下面的格式输出：
---
title: example_title
subtitle: example_subtitle
tags: [tag1, tag2]
author: author_name
date: yyyy-mm-dd
---
5. 这个程序可以部署在github page，使我可以通过网页直接使用。
6. 这个程序可以使用任何你认为最适合的编程语言。
'
3. 微调后让它美化了页面，然后就这样了。
