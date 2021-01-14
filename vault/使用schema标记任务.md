---
id: 3264b03c-f522-4ac6-84e7-760b52568cb1
title: 使用Schema标记任务
desc: ''
updated: 1610589790203
created: 1610589745056
---

## 使用Schema标记任务

```yml
version: 1
imports: []
schemas:
  - id: readme
    children: 
    - denron入门
    - test
    title: readme
    parent: root
  - id: test
  - id: denron入门
    children:
      - denron入门.使用笔记
      - denron入门.使用链接
  - id: denron入门.使用笔记
  - id: denron入门.使用链接

```