---
date: '2026-06-08T09:10:29+09:00'
draft: true
title: 'hugoの使い方 gitでの更新方法'

ShowToc: true
---

## hugoでよく使うコマンドとか
まずは[ここ](https://gohugo.io/getting-started/quick-start/)を参照すること

- contentの追加\
`hugo new content content/posts/my-first-post.md`

- serverのデプロイ
`hugo server --buildDrafts`\
or\
`hugo server -D`\

hugoのDocsは[ここ](https://gohugo.io/documentation/)

## gitでのcomit, push
1. `git branch`
2. `git diff`\
差分を表示。抜ける時はqキーを押す
3. `git add xxx`\
雑にやるなら`git add -A`
4. `git commit -m "any comment"`
5. `git push origin main`

## その他、PaperModについて
[PaperMod Wiki](https://github.com/adityatelange/hugo-PaperMod/wiki)