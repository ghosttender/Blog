---
title: test
date: 2025-12-24 14:06:43
tags:
---



# 这是一级标题


>互联网的朋友们大家好~
>这里是引用内容

在_config.butterfly.yml 文件中将以下妹纸进行修改，可以实现首页打字机特效：

'''yaml
subtitle:
    enable: false
    effect: true
    typed_option:
    source:false
    sub:
'''

修改为：

'''yaml
subtitle:
    enable: true
    effect: true
    typed_option:
    source: 3
    sub:
        - My First Blog
        - I LOVE FISHC
'''