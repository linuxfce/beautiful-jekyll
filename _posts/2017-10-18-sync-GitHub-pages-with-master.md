---
layout: post
title: Sync gh pages with master
---

## Easily keep gh pages in sync with master

```
$ git add .
$ git status // to see what changes are going to be committed
$ git commit -m 'Some descriptive commit message'
$ git push origin master

$ git checkout gh-pages // go to the gh-pages branch
$ git rebase master // bring gh-pages up to date with master
$ git push origin gh-pages // commit the changes
$ git checkout master // return to the master branch
```

#### This guide was written by [Lea Verou](https://lea.verou.me/2011/10/easily-keep-gh-pages-in-sync-with-master/)
