# JIRA

> 이슈 트래킹 시스템
>
> 다양한 기능과 지표 관리 제공으로 높은 점유율을 차지하고 있음

<br>

## JIRA를 왜 쓰는가?

> 프로젝트 관리
>
> 협업
>
> 트러블슈팅

새로운 업무가 생겼을 때 자세한 업무 내용을 사람들에게 물어보거나 하는 불필요한 시간 낭비를 줄일 수 있음

업무를 어떻게 수행했는지 한 눈에 알 수 있음

<br>

#### `JIRA 사용 예시`

> 다양한 가젯을 활용해 프로젝트 일정 및 진행상황 관리 가능

![image-20210709224541154](README.assets/image-20210709224541154.png)

<br>

## 기능

#### `Active sprint`

>  작업을 To do - In Progress - Done 으로 나눠 관리하는 board

<br>

#### `Workflow`

> 위에서 작성한 업무 리스트를 순서도 형식으로 정리
>
> `To do` : 이슈등록
>
> `In progress` : 작업중
>
> `Done` : 작업 완료

- **burndown chart (중요!!)** : 매일 정해진 시간에 policy 업데이트. JIRA의 대표적인 output

  ![image-20210630095156726](README.assets/image-20210630095156726-1625014319633.png)

<br>

#### `Story point`

> 작업 난이도 : 능력 편차가 심한 회사 직원들에게 각자의 능력에 맞는 난이도의 업무 하달
>
> SSAFY는 `man-month`로 사용
>
> 다른 회사 대부분도 man-month로 사용

![image-20210630095601142](README.assets/image-20210630095601142.png)

<br>

<br>

## JIRA를 어떻게 어필할까

> 포트폴리오에 활용 가능
>
> - 꾸준히 작업, 일정 관리, 문서화 정리 등을 잘 했는지 
>
> Scrum, Kan-ban 둘 다 괜찮다
>
> **이슈 등록은 다 같이! 완료 처리는 등급에 따라 권한 부여!**





<br>

# DevOps

> 개발 + 운영 (Development + Operations)

#### `DevOps를 잘 수행하기 위한 조건`

- 반복적인 작업들을 Tool을 이용해 자동화

- 팀원 모두가 알고 있는 하나의 공유된 지표가 필요

- 장애나 이슈가 있을 때 혼자만 알지 말고 팀원들과 공유 필요 -> `JIRA`



## JIRA 사용법

Issue Type

- stroy
  - ex) 사용자가 로그인을 한다
- Epic
  - 하나의 큰 틀
  - 한 테마?
  - 내가 필요한 이슈, 스토리를 넣어서 관리



#### 스크럼보드

- 스프린트별로 관리



## JQL

> Jira Query Language

- JIRA 이슈를 구조적으로 검색하기 위한 명령어
- SQL과 비슷하나 사용하는 필드가 다름



#### `JQL field`

> summary : 이슈 제목
>
> 



#### `JQL operator`

> =, !=, >, >=
>
> in, not in
>
> ~ (contains), !~ (not contains)
>
> is empty, is not empty, is null, is not null





