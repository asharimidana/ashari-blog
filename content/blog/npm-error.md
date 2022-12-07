---
draft: false 
date: 2022-09-08T13:39:18+08:00
title: "Cara atasi Npm Error"
description:
slug: npm-error
type : blog
author: ari
tags:
    -  npm

categories:
    - 

---

You need to set npm config registry just like this.

``` shell
# 1) Delete proxies
npm config rm proxy
npm config rm https-proxy

# 2) Change Timeouts
npm config set fetch-retry-mintimeout 20000
npm config set fetch-retry-maxtimeout 120000
