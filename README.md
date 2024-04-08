https://www.notion.so/teamsparta/KPT-1fa8921332e5464c9049e94493b05eec

# KPT

- `*KPT 회고 방법론**`을 적용해 봅니다.
- `Keep` : 이번 프로젝트에서 진행한 과정 중 다음 프로젝트에서도 **유지했으면 하는 부분**.
- `Problem`
    - 문제점 : 이번 프로젝트에서 발생한 **문제점**을 객관적으로 판단
    - 해결 방안 : 해당 문제점을 **해결할 수 있는 현실적인 방안** 제시
- `Try` : 다음 프로젝트를 위해 해야 할 **노력**
    - `Feel` : 이번 프로젝트를 통해 **느낀 점**

## Keep

- commit 컨벤션 유지하기!!
- git PR작성하기

## Problem

- 문제점
    - ViewController의 역할이 명확하지 않았다.
    - 각자의 swift 파일 내에서 class별로 extension이 정의되었다.
    코드를 다소 읽기 어렵게 하는 원인이 아니었을까 생각해본다.
    - 메뉴 리스트를 따로 파일을 만들어 넣었어야 했는데 그러지 못했다.
    - git에서 branch 설정이나 pull, merge 등을 원활히 하지 못해 문제가 발생했다.

- 해결방안
    - MVC 패턴을 적용하도록 노력하자 (Model - View - Controller)
    - 와이어프레임부터 좀더 체계적으로 완성하고 진행
    - 상황에 맞게 파일 분류를 좀 더 체계적으로 해줘야 할 것 같다.

## Try

- Xcode 내에서 팀원 간 줄바꿈, 주석 컨벤션을
Git 내에서 Commit, Branch 컨벤션 설정을 통일해보자.
- MVC 패턴이란?  참고 : https://m.blog.naver.com/jhc9639/220967034588
- 엡개발을 위한 와이어프레임 작성을 위한 사이트   참고 : https://brunch.co.kr/@mayo-ux/5
