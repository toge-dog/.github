
## 함께걷개 

### 프로젝트 소개
- 1500만 반려인들을 위한 플랫폼입니다.
- 현재 위치를 기반으로 매칭 메이트를 찾을 수 있습니다.
- 지도에 마커를 찍고 친구 추가와 매칭 시스템이 핵심 기능입니다.
- 개발 기간 : 2024.08.08 ~ 08.29
- URL : http://toge-dog.com
<br>

### 구성원
<table>
  <tbody>
    <tr width='100%'>
      <th align="center" width='10%'>황진혁</th>
      <th align="center" width='17%'>신민준</th>
      <th align="center" width='14%'>남채연</th>
      <th align="center" width='17%'>양수명</th>
      <th align="center" width='19%'>이광희</th>
    </tr>
    <tr>
      <td align="center"><img width="100" alt="image" src="https://github.com/toge-dog/.github/blob/main/assets/hwang.jpeg?raw=true"></td>
      <td align='center'><img width="100" alt="image" src="https://github.com/toge-dog/.github/blob/main/assets/shin.jpeg?raw=true"></td>
      <td align='center'><img width="120" height="130" alt="image" src="https://github.com/toge-dog/.github/blob/main/assets/nam.jpeg?raw=true"></td>
      <td align='center'><img width="100" alt="image" src="https://github.com/toge-dog/.github/blob/main/assets/yang.jpeg?raw=true"></td>
      <td align='center'><img width="100" alt="image" src="https://github.com/toge-dog/.github/blob/main/assets/lee.jpeg?raw=true"></td>
    </tr>
    <tr>
      <td width="150"><a href="https://github.com/JINHYEOKKK">@JINHYEOKKK</a></td>
      <td width="150"><a href="https://github.com/Tizesin">@Tizesin</a></td>
      <td width="150"><a href="https://github.com/chaeneeee">@chaeneeee</a></td>
      <td width="150"><a href="https://github.com/Lifesheep1">@	Lifesheep1</a></td>
      <td width="150"><a href="https://github.com/gwanghui97">@gwanghui97</a></td>
    </tr>  
  </tbody>
</table>
<br>

### 프로젝트 아키텍쳐

<img src="https://github.com/toge-dog/.github/blob/main/assets/architecture.png?raw=true" alt="Project togedog_wireframe" width="600">

<br>

- CI/CD 파이프 라인을 구축하여 IntelliJ에서 main 브랜치에 push를 하면 자동으로 통합되고 배포되도록 설정하였습니다. AWS EC2에 Docker와 Docker Compose를 활용하여 배포를 하였고, S3에 React 코드를 배포하고 사진 업로드 기능을 구현하였습니다.
<br>

### 개발환경
 - 개발도구: Intellij IDEA
 - 언어: Java 11 Open JDK
 - 빌드도구: Gradle
 - 개발
    - Spring Framework: 5.3
    - Spring Boot: 2.7.0
    - Spring Data
      - Spring Data JPA
      - Spring Data Redis
    - Spring Security
    - JPA
 - 데이터베이스
    - MySQL: 8.0.25
    - Redis
 - ERD
    - ERDCloud
 - 프론트 개발 환경 및 언어
    - 언어:
      - HTML
      - CSS
      - JavaScript
    - 라이브러리 및 프레임워크:
      - React
      - React Query
      - React Bootstrap 5
      - Axios
 - 형상관리 및 이슈관리
    - GitHub
 - 기타
   - Slack
  
### 사용도구

<span>
  <img src="https://img.shields.io/badge/spring boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/spring security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
  <img src="https://img.shields.io/badge/spring Data JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <img src="https://img.shields.io/badge/spring Data Redis-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=React&logoColor=white">
  <img src="https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=ReactQuery&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=Docker&logoColor=white"/>
  <br>
  <img src="https://img.shields.io/badge/Github Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white"/>
</span>

### etc

<span>
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white"/>
  <br>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=Slack&logoColor=white">

  
</span>


### ERD
![image](https://github.com/toge-dog/.github/blob/main/assets/erd.png?raw=true)
<br>

### [Kanban Board](https://github.com/orgs/nhnacademy-be5-T3Team/projects/2/views/9)
Github Kanban
- Github의 Project 기능 중 Kanban 보드를 활용하여 프로젝트를 관리했습니다.
- Todo, InProgress, Done 의 열로 작업을 구분해 현재 작업 상황을 실시간으로 확인할 수 있도록 했습니다.

<img width="1713" alt="image" src="https://github.com/toge-dog/.github/blob/main/assets/kanban.png?raw=true">
<br>

### 🔍서비스 구현 내용

### 🕹주요 기능

| 랜딩 페이지 | 회원가입 |
| :---: | :---: |
| <img src="https://github.com/toge-dog/.github/blob/main/assets/landing_page.gif?raw=true" width="370" height="200"/> | <img src="https://github.com/toge-dog/.github/blob/main/assets/signup.gif?raw=true" width="370" height="200"/> |

| 로그인 실패 및 성공 | 마이페이지 |
| :---: | :---: |
| <img src="https://github.com/toge-dog/.github/blob/main/assets/login_fail_success.gif?raw=true" width="370" height="200"/> | <img src="https://github.com/toge-dog/.github/blob/main/assets/mypage.gif?raw=true" width="370" height="200"/> |

|  게시글 작성  | 댓글 작성 |
| :---: | :---: |
| <img src="https://github.com/toge-dog/.github/blob/main/assets/wirte_board.gif?raw=true" width="370" height="200"/> | <img src="https://github.com/toge-dog/.github/blob/main/assets/comment.gif?raw=true" width="370" height="200"/> |

| 자랑 게시판 | 마커 그리기 |
| :---: | :---: |
| <img src="https://github.com/toge-dog/.github/blob/main/assets/boost_board.gif?raw=true" width="370" height="200"/> | <img src="https://github.com/toge-dog/.github/blob/main/assets/marker.gif?raw=true" width="370" height="200"/> |

| 매칭 요청하기 | 매칭 요청 수락하기 |
| :---: | :---: |
| <img src="https://github.com/toge-dog/.github/blob/main/assets/matching_request.gif?raw=true" width="370" height="200"/> | <img src="https://github.com/toge-dog/.github/blob/main/assets/matching_request_accept.gif?raw=true" width="370" height="200"/> |

| 친구 요청하기 | 친구 요청 수락하기  |
| :---: | :---: |
| <img src="https://github.com/toge-dog/.github/blob/main/assets/matching_request.gif?raw=true" width="370" height="200"/> | <img src="https://github.com/toge-dog/.github/blob/main/assets/friend_request_accept.gif?raw=true" width="370" height="200"/> |


### 구성원 별 담당 내용

## 황진혁

> ## 프로젝트 설계 및 문서화
- 사용자 요구분석서 설계
  * 기능에 따른 사용자의 요구 사항과 제한 사항 분류
  * 각 기능에 대한 우선 순위 정렬
- API 명세서 설계
  * 기능별 method, URI, Request/Response 상세 설계
- ERD 설계
  * 회원, 친구, 반려동물 테이블 설계 및 관계 설정

> ## 백엔드 구현
### 회원 관리
- 회원 CRUD 및 Validation 구현
- JavaMailSender를 이용한 이메일 인증 구현
- JWT와 Redis를 활용한 인증 시스템 구현
  * 로그인 시 JWT 토큰 발급 및 Redis 저장
  * 로그아웃 시 Redis에서 토큰 삭제
 
> ## 친구 관리
- 친구 요청, 수락, 거절 등 Status에 따른 CRUD 구현

> ## 반려동물 관리
- 반려동물 정보 CRUD 구현

> ## 프론트엔드 구현
- 친구 관리 페이지 구현
- 게시판 페이지 CSS 적용

> ## 사용 기술
- Backend: Spring Boot, JPA, Redis
- Frontend: React 
- Database: MySQL
- 기타: JWT, JavaMailSender

> ## 주요 기능
- 회원 인증 및 관리
- 친구 관계 관리
- 반려동물 정보 관리
- 이메일 인증
- 토큰 기반 인증 시스템

---
<br/>

## 신민준

> ## 프로젝트 설계
  - 사용자 요구분석서 설계
  - 기능에 따른 사용자의 요구 사항과 제한 사항을 분류
  - 각 기능에 대한 우선 순위 정렬
  - 각 요구에 따른 테이블 내 Status 관리
        
> ## API 명세서 설계
  - 기능 별 method 및 uri 설계
  - 기능 별 Request Header & Body 설계
  - 기능 별 Response Status Code & Header & Body 설계
  
> ## ERD 설계
  - 비정규화를 통한 데이터 검색 속도 향상
  - 싱글테이블 전략을 이용하여 게시판 ERD 설계
  - 테이블 연관관계 설계

> ## 환경구성
  - exception
    - 사용자 요구 예외처리 및 반환 코드 작성 환경 구성

  - PageNation 환경 구성
    - 제네릭을 통한 PageNationDto 설계

  - Auditable
    - Entity에 적용할 공통사항 추상화 SuperClass 설계

> ## Security
  - JWT 토큰
    - 로그인 시 사용자 정보 Base64SecretKey로 Encoding
    - api 요청 Header안의 AccessToken값 Decoding을 통한 사용자 인증절차 구현

  - 사용자 권한
    - 사용자의 계정에 따라 Admin / User 권한 부여

> ## EventListener
  - CustomEvent
    - 커스텀 이벤트를 적용하기 위한 전용 트리거 설계

  - EventListenerService
    - 이벤트 리스너를 이용하여 각 비즈니스 로직간의 결합도 하향
    - Test Code 설계에 유리한 환경 구축

> ## Matching
  - 매칭
    - 사용자의 매칭 정보 및 Status CRUD 설계

  - 매칭 대기열
    - 사용자의 매칭 수락 및 거절에 따른 Status CRUD 설계
    - Hibernate 최적화를 위한 JPQL 적용
    - 데이터 정합성을 위한 ReentrantLock 기능 구현

> ## Scheduler
  - 스케줄러
    - 데이터 정합성을 위한 주기적으로 비정규화 데이터베이스 정합성 검증 진행
    - 비동기 스케줄러 구축
    - 비동기 멀티쓰레드 Config 설계를 통한 과도한 메모리 사용 방지

> ## Landing Page
  - 디자인 및 애니메이션
    - 랜딩페이지 디자인 설계 및 적용
    - Full-Page-Scroll 적용
    - 대표 게시글 Slide Card Board 디자인 설계 및 애니메이션 적용

> ## 매칭 modal
  - 매칭
    - axios를 통한 매칭 정보 CRUD 요청 구현
    - boot-strap을 이용한 modal 디자인 설계
    - 부모/자식 컴포넌트간 동시적 CSS 변경을 위한 props 설계
    - 적응형 레이아웃 적용

---
<br/>

## 남채연


---
<br/>

## 양수명

> ## 프로젝트 설계 및 문서화
- ﻿사용자 요구사항 분석 및 기능 우선순위 설정:
  - ﻿사용자 요구사항 분석서를 작성하여 기능별 요구사항과 제한사항을 명확히 구분
  - ﻿각 기능의 중요도와 구현 우선순위를 체계적으로 정렬하여 프로젝트 일정 최적화
- API 명세서 설계
  - ﻿각 기능에 맞는 메서드(Method) 및 URI를 설계하여 명확한 API 구조 정의
  - ﻿Request Header 및 Body, Response Status Code, Header, Body에 대한 세부 설계를 통해 통신 안정성 및 데이터전송의 일관성 확보
- ERD 설계
  - ﻿싱글 테이블 전략(Single Table Strategy)을 이용하여 게시판 구조의 ERD(Entity-Relationship Diagram)를 설계

> ## ﻿게시판 기능 구현:
  - ﻿싱글 테이블 전략을 활용한 게시판 카테고리 설계 및 구현
  - ﻿게시글 작성, 수정, 삭제 기능을 설계 및 구현
  - ﻿댓글 및 대댓글 기능을 설계하고, 계층 구조를 통해 구현
  - ﻿좋아요 기능 설계 및 구축
  - ﻿조회수 기능을 설계 및 구축
    
---
<br/>

## 이광희

> ## 인프라

- **CI/CD 및 배포**
    - 기본적인 CI/CD 환경 구축
        - Github Actions를 통한 CI/CD 환경 구축
     
    - 빌드 시 민감 정보 처리 과정
        - 프로젝트 내의 인증서 또는 키파일 등이 공개 레포지토리에 올라가지 않도록 제외하고,
          프로젝트 빌드 과정에 필요한 인증서 또는 키파일 등이 CI/CD 과정상에서 동적으로 생성되어 빌드시 포함되도록 설정

    - Docker Compose를 통한 다중 컨테이너 관리
      - Spring, Mysql, Redis를 컨테이너 기반으로 관리

> ## 배포

- **AWS**
  - AWS EC2
    - AWS EC2에 Docker를 활용한 Spring, Mysql, Redis 서버 배포

  - AWS S3
    - AWS S3에 프론트엔드 서버 배포

  - 도메인
    - 구입한 도메인 주소에 연결하여 배포

> ## 파일 업로드
  - 회원 가입, 게시글 등록 시에 AWS S3에 이미지 등록 기능 구현

> ## 프론트엔드
  - **Page 구현**
    - 랜딩 페이지 구현
    - 로그인, 회원가입 페이지 구현
    - 상속 관계 테이블에 맞게 게시판 페이지 구현

  - **React Query**
    - 캐싱을 효율적으로 관리
    - 백그라운드에서 오래된 데이터를 업데이트 하도록 설정
    - 페이징처리, 지연 로딩 데이터 성능 최적화
  
  - **Custom Hook**
    - Custom Hook을 개발하여 전역 상태 관리
    - 새로고침 시에 상태값 유지

  - **토큰 기반 로그인 구현**
    - 회원 가입을 한 사용자만 로그인이 되는 기능 구현
    - 로그인을 하면 랜딩 페이지로 redirect 되고 회원 가입 시 입력한 별명 노출


> ## 프로젝트 초기 설정
  - 버전에 맞게 프로젝트 초기 설정
  - gitignore에 민감한 정보 제외


<br>

## 개발 문서

### 요구사항 정의서
[togedog-요구사항 정의서](https://docs.google.com/spreadsheets/d/12T5KpHvGmHHc-rV3AOWUxChp-mg3O3M22-zKpQ6agxM/edit?gid=1288555931#gid=1288555931)

### API 명세서
[togedog-API명세서](https://docs.google.com/spreadsheets/d/12T5KpHvGmHHc-rV3AOWUxChp-mg3O3M22-zKpQ6agxM/edit?gid=835394422#gid=835394422)

## 프로젝트 회고


### 황진혁
> 이번 프로젝트는 처음으로 협업하여 웹 개발을 해본 소중한 경험이었습니다. 처음 만난 팀원들과의 소통이 정말 잘 되었고, 의견 충돌이 있어도 서로의 입장을 이해하며 잘 풀어나갈 수 있었습니다. 다만, 설계 단계에서 ERD, API 명세서, 화면 목업 작성이 부족해 많은 수정이 필요했던 점이 아쉬웠습니다. 특히 백엔드와 프론트엔드 간의 API 연계에서 수정이 잦아져서 머리아프고 힘든 순간이 많았습니다. 앞으로는 팀원들과 매일 회의를 통해 상황을 점검하고, 안 될 것 같으면 빠르게 포기하고, 그 에너지로 완성도 높은 결과물에 쏟아붓는 게 더 낫겠다는 생각이 들었습니다.

<br>

### 신민준
> 비슷한 실력대의 사람들과 협업하여 진행하는 프로젝트라 걱정과 설렘이 많았던 것 같습니다. 다행히 모두 대화도 잘 통하고 협업에 긍정적인 자세를 가지고 계셔서 트러블 없이 진행되었습니다. 학원 내에서 처음으로 진행하는 프로젝트였기에 스케줄 관리가 미흡한 부분이 있어, 후반부에 다소 체력적으로 무리를 하며 진행하게 되었습니다. 차후 진행될 프로젝트에서는 여러 상황을 고려하여 스케줄 관리 및 설계와 컨디션 관리를 철저히 해야겠다고 생각했습니다.

<br>

### 남채연

<br>

### 양수명
> 첫 프로젝트를 훌륭한 팀원들과 함께할 수 있어 정말 좋았습니다. Git과 GitHub 사용법, 협업 프로세스, 기능적인 부분 등 몰랐던 것들을 많이 배울 수 있었던 유익한 시간이었고 문서화의 중요성도 깨달았습니다. 아쉬웠던 점은 백엔드 위주로 개발을 진행해서 프론트엔드를 하지 못해 아쉬웠었고 다음 프로젝트 때는 백엔드와 프론트엔드도 같이 진행하고 싶습니다. 이번 팀 프로젝트를 통해 제가 알지 못하는 기술 스택이 많다는 것을 느꼈고, 그만큼 배울 것도 많다는 것을 깨달았습니다. 마지막으로, 화목한 분위기에서 협업할 수 있어서 좋았고, 모르는 부분이 있을 때 친절히 알려준 우리 팀원들에게 진심으로 감사드립니다.

<br>

### 이광희
> 제대로 된 협업을 경험해본 것 같습니다. 기존에 했던 프로젝트와는 다르게 요구사항 분석, API 명세서를 꼼꼼히 작성하며 최대한 실무와 가깝게 문서화 하려고 노력했습니다. 힘들 때도 많았지만, 성장하는데 시너지가 되는 팀원들을 만나서 좋은 경험이었습니다. 힘들었지만 재미있었고 해보고 싶었던 프로젝트 아키텍처 설계와 CI/CD, React Query를 사용하여 최신 기술을 익혀서 많은 성장을 했다고 생각합니다.

<br>
