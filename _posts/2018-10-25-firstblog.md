---
layout: post
title: "Vim 与中文输入法"
subtitle: 'Using Vim with non-english input method'
author: "Hux"
header-style: text
tags:
  - Vim
---

Update: 我最后还是放弃在 Vim 模式下输入中文了，mental model 的 cost 太重了（

---

我相信很多中文世界的 Vimer 都遇到过这个烦恼，在 vim 的 insert 模式时可能突然想输个中文，输完之后会本能的直接 `esc` 接 normal 模式操作，结果发现跳出来的是中文输入法……对于 vscode，我一般会在几次错误之后被逼到退出 vscode vim 模式，而对于终端中用的 neovim，就只能尽量不输入中文了。

