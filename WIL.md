# 김효식, 김민성, 송진영의 학습기록

## 혼자 하는 git flow process - 김효식
1. 생성한 레포지토리를 `git clone` 받습니다.
2. 해당 디렉토리로 이동하여 `git flow init`명령어로 `git flow`를 시작합니다.
- 특이사항이 없다면 브랜치명을 기본값으로 유지합니다.
3. `git flow feature start feature명`으로 새로운 `feature`를 생성합니다.
4. 작업을 하고, `add, commit`을 하고, `git flow feature finish feature명`으로 `feature`를 종료합니다.
5. `git flow release start v버전명`으로 릴리즈 브랜치를 생성합니다.
6. 해당 작업이 끝나면 `git flow release finish v버전명`으로 릴리즈를 종료합니다.
7. `develop`브랜치와 `main`브랜치의 내용을 각각 `remote`에 `push`합니다.
8. 생성한 태그도 `git push --tags`로 올려줍니다.
