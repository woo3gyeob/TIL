# Git

<br>

#### `싱글(개인) 플레이`

- 코드 관리/백업 용

#### `멀티(팀) 플레이`

- 협업 Workflow
- 서비스/제품 이력 관리
- 커밋 규칙과 정확한 메시지
- 코드 리뷰

**Git은 branch로 소스코드를 관리할 수 있다는 점에서 최고의 장점을 지님!**

<br>

## Git Conflict

> 브랜치로 협업을 하면서 발생할 수 있는 Git 충돌

#### `브랜치 생성 git 명령어`

git 초기화

```bash
git init
```

브랜치 생성

```bash
git branch [브랜치명]
```

브랜치 변경

```bash
git switch [브랜치명]
```

git add/commit/push

```bash
git add .
git commit -m '커밋메시지'
git push origin [브랜치명]
```

<br>

상황 1. **A 브랜치로 push**한 내용을 **B가 로컬**에서 **master** 브랜치로 받으려면,

- gitlab에서 merge request로 A 브랜치 내용을 master 브랜치에 병합
- B 로컬에서 master 브랜치로 git pull 받으면 됨

-> B에서 master 브랜치 이외의 브랜치로 pull 받게 되면?

- B가 다른 브랜치로 작업한 내용 사라지게 됨!

<br>

상황 2. A와 B가 같은 파일을 수정하고 둘 다 다른 브랜치로 push 했을 때

- gitlab에서 A 브랜치 MR하고 B 브랜치 merge에서 충돌 발생

- B 브랜치 로컬에서 master pull (gitlab에서 어떻게 하라고 나옴)

- B 브랜치에서 push master

- **A에서 작업한 내용 commit 해야함! (이거 진짜 중요!!)**

- A에서 pull master

- A에서 vscode에서 보면 양 쪽 수정사항이 다 보이고 어떤거 적용할지 선택 가능

- 둘다선택

- A 브랜치에서 add/commit/push

- 둘 다 반영 ok

