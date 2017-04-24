
# Practical Git: Remove unnecessary git tracking with .gitignore files


```

```

rm -rf .git/




```
// 초기화
git init
ls -a

// github remote repo 연결하기
git remote add origin https://github.com/stuckyi/usingGit.git 

// remote repo 확인
git remote -v
```


## Practical Git: Capture code history snapshots with git add/commit/push

Git 을 사용하여 작업할 때  개발자가 수행하는 가장 일반적인 작업은 `stage`, `commit`, `push` 하는 것이다. "edit - stage - commit - push"는 git 사용시 일반적으로 활용도는 작업흐름이다.

개발자는 코드베이스의 변경 사항을 "snapshot" 하여 공유하고 되돌릴 수 있다. 이 강의에서는 코드베이스를 변경한다음 add(stage), git commit(history sotre), git push(원격저장소와의 동기화)등을 실행해보고, 이와함께 현재 작업중인 git 변경사항을 확인할 수 있도록 `git status`를 활용해보고 싶다.
