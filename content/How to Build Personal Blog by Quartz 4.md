---
title: How to Build Personal Blog by Quartz 4
draft: "true"
tags:
  - blog
  - "#quartz"
created: 2025-12-09 23:40
modified: 2025-12-10 21:05
---
Quartz 4 is so brilliant to build personal blog easily.
You can follow me to set the most useful and simplest blog, or go with [Welcome to Quartz 4](https://quartz.jzhao.xyz/) for more details.

## 0. Before Start
You need
1. Github account (Free!)
2. A computer
3. Network(Maybe VPN is necessary)
4. Obsisian(Optional, but I think it's the best note editor)

Have a look to my blog: [Welcome to Sisyphus Mountain](https://sisyphus-mountain.github.io/)

## 1. Environment
## git
https://git-scm.com/install/windows

## Node.js
[Node.js — Download Node.js®](https://nodejs.org/zh-cn/download)
Get a prebuilt Node.js for Windows is enough.

## Validate Installation
Open PowerShell or CMD:
```bash
git --version
node --version
npm --version
```

# 2.Set Quartz

Select a parent folder you like,  and click right to open Terminal.
Then,
```bash
git clone https://github.com/jackyzha0/quartz.git
cd quartz
npm i
npx quartz create
```

Now, we are at `/quartz`, enter the sub folder `/content`, and you can see `/content/index.md`, which is the home page.

It's very recommended that you use Obsidian and set the folder `/content` as your vault.

