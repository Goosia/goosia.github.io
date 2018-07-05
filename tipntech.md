---
title: Oh My Tips
subtitle: 깨알정보
layout: "page"
icon: fa-bolt
order: 3
---

# 오늘의 팁

# 자바(Java)
* 이클립스 혹은 STS 초기 설치 후 jdk 관련 에러는 java build path 에 연결된 jre가 program files 아래 jre 인지 확인 후 jdk 아래 jre 로 연결을 변경하자.
* maven 서명 에러가 발생할 경우 해당 라이브러리를 삭제하고 다시 받아라
* 설정 변경 및 오류 수정 후 항상 project - clean 해라
* constant string long 발생하면 string.append 로 줄을 나눠라
* maven build 4번은 이전 goal 명령, 5번은 신규 명령 maven build 이다


# 깃(Git)
* Visual Studio Code 사용 중에 깃헙에 소스를 동기화 할때 항상 유저 아이디와 암호를 입력 받는데 인증 정보를 저장하는 방법은 : 깃 루트에서 git config credential.helper store 입력 후 로그인 하면 이후 부터는 자동 인증 된다.
​
{%- include disqus.html -%}