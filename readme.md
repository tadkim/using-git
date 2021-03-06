
# Readme

readme 파일을 추가하여 프로젝트에대한 정보를 소개하는 것은 하나의 컨벤션이 되었다. `.md` 라는 확장자는 markdown 파일을 의미한다. 마크다운은 문서를 보다 편한게 작성하기위해 만들어진 Document 규칙이라고 생각하면 좋다.

간단하게 작성하고, commit & push 하여 github에서 확인해봐도 좋다.

```
getRandomElement(){
    // some logic.
}
```


## Practical Git: Sync local and remote repos with git pull

`git pull`을 활용하면 프로젝트의 원격저장소에서 최신 변경사항을 가져와서 로컬 코드와 병합(결합)할 수 있다. 
이 강의에서는 `git pull`을 사용하여 `git fetch와 git merge`를 실행하는 방법을 알려드립니다.

`git pull`은 `git fetch`와 `git merge`를 동시에 실행하는 명령어이다. 



- `git fetch` : 원격 저장소의 최신 변경 사항을 가져와서 로컬에 저장하지만 실제로는 해당 local code에 포함시키지는 않는다.
- `git merge` : 이 명령어는 `git fetch`에서 얻은 변경 사항을 실제 코드로 병합하도록 로컬 저장소에 지시한다.

원격저장소에서 readme.md 파일 변경



```
// 새로운 branch 생성하기

git branch new-feature
git branch

```

##  Practical Git: Sync branches with git merge

여기서는 feature branch를 만들고 이것을다시 master branch에 결합하는 방법에 대한 작업흐름을 살펴본다.



```
function getURLSlug(words) {
    return words
        .replace(/\s+/g, '-')
        .toLowerCase();
}
```