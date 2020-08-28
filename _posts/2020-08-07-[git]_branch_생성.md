---
title: git 과거 커밋 수정
tags: git
---

### git log

```git checkout -b test-branch```

<!--more-->

---

로컬에서 브랜치 생성
```sh
git checkout -b test-branch
```


remote branch에 push
```sh
git push origin test-branch
```


local - remote 브랜치 연동 작업
```sh
git branch --set-upstream-to origin/test-branch
```
