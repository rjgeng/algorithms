---
layout: default
---

# Code signal Arcade

```
rm -rf algorithms-arcade
rm .gitmodules
rm -rf .git
git init
git branch -M gh-pages
git remote add origin git@github.com:rjgeng/algorithms.git
git submodule add git@github.com:algorithms-arcade/algorithms-arcade.git
git add .
git commit -m 'first commit'
git push origin gh-pages --force
```
