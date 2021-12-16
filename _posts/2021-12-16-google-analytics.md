---
layout: posts
title: "블로그에 Google Analytics 적용하기"
comments: true
---

이번 포스팅에서 Jekyll을 이용해 만든 이 블로그에 Google Analytics를 적용해보려고 한다.

### 1. Google Analytics란?
---

Google에서 지원하는 통계 분석 시스템이다. 이걸 통해서 블로그에 방문한 사람들의 통계를 내보고 분석해보려고 한다.
     
    
### 2. 내 블로그에 적용해보기
---

아래는 적용하는 순서이다.
   
 1. 먼저 [Google Analytics 사이트](https://analytics.google.com/) 에 접속해서 계정을 생성한다.      
   
 2. 계정 생성 후에 G 태그 형태로 나오는 traking ID를 복사해둔 후 보관한다.   
   
 3. 로컬 저장소의 '_config.yml' 파일을 연 후 아래처럼 설정해준다.   
 (minimal-mistakes 테마를 기준으로 적용한 모습입니다.)
   
 ![Analytics](/assets/img/analytics.png)
   
이제 다시 Google Analytics 사이트로 돌아가서 조금 기다린 후 블로그를 접속해보고, 사용자를 체크해보자.

 ![User](/assets/img/user_count.png)

잘 적용된 걸 확인할 수 있다~