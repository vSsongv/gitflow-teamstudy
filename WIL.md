# 김효식, 김민성, 송진영의 학습기록

- Milestone: 큰 작업 단위로, 'first Sprint'같은 것이 예시가 될 수 있다.- Issue: Milestone의 해야 할 일들 하나하나를 issue로 볼 수 있다. 프로젝트, 레포와 관계된 모든 해야할 일과 버그, 개선사항 등을 기록1. 먼저 팀장이 repo를 만든다.
2. 팀원들은 issue를 생성한 후, fork를 한다.
3. fork뜬 repo를 clone한 후, 해당 repo로 이동한 후, gif flow init을 해준다.
4. git remote로 팀장 repo remote를 추가한 후 pull을 받는다.
4. git flow start를 한 후, 개발을 시작한다.
**2021.09.30~2021.10.01**

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
