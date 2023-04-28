---
layout: post
title: 常用的 Git 配置
author: Pear
tags: Git 笔记
date: 2023-04-28 15:32 +0800
---

# 多个账号
```
[user]
    name = $Username
    email= $Email
    signingkey = $Path_to_ssh_or_gpg_keys
```
# 使用ssh密钥签名
```
[commit]
    gpgsign = true
[gpg]
    sign = ture
    format = ssh
```