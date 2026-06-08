---
date: '2026-06-08T09:57:37+09:00'
draft: true
title: 'Markdown Cheetsheet'

ShowToc: true
markup:
    tableOfContents:
        endLevel: 3
---

Markdown初心者のため、Markdown記法のチートシートをまとめます。\
hugoで使えるものを基準にまとめます。(goldmark?)

## 基本のシンタックス
すべてのマークダウンアプリケーションはこれらが使えるらしい。

### ヘッダー
---
```
# H1
## H2
### H3
```
#### 表示
# H1
## H2
### H3

### 太字、斜字
---
```
**bold text**
*italicized text*
```
#### 表示
**bold text**\
*italicized text*

### 引用
---
```
> blockquote
```
#### 表示
> blockquote

### 数字付きリスト
---
```
1. First item
2. second item
3. third item
1. wtf
```
#### 表示
1. First item
2. second item
3. third item
1. wtf

数字はなんでもいいっぽい？

### 箇条書きリスト
---
```
- First
- Second
- Third
```
#### 表示
- First
- Second
- Third

### インラインコード、コードブロック
---
````
`This is inline code`
```
This is code block
```
````
#### 表示
`This is inline code`
```
This is code block
```
詳しくは[hugoのDocs](https://gohugo.io/content-management/syntax-highlighting/)を参照

### 水平線
---
```
--- or *** or ___
```
#### 表示
---
