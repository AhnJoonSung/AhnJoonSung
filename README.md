<!-- Intro -->

<img src="https://capsule-render.vercel.app/api?type=waving&color=7FBCD2&height=200&section=header&text=안준성입니다&fontSize=30&fontAlignY=40&desc=&descAlignY=65&animation=twinkling" />

<p align="center">
  <a href="https://velog.io/@tjdtna01/posts">
    <img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=Velog&logoColor=white"/>
  </a>
  <a href="mailto:tjdtna01@naver.com">
    <img src="https://img.shields.io/badge/Naver%20Mail-03C75A?style=flat-square&logo=naver&logoColor=white"/>
  </a>
</p>

---

###  🔧  기술 스택
**Programming Language**  
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

**Framework**  
![SpringBoot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Django REST](https://img.shields.io/badge/Django%20REST-092E20?style=for-the-badge&logo=django&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)

**Database**  
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white)
![SpringDataJPA](https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-DC382D?style=for-the-badge&logo=mybatis&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**DevOps**  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**etc**  
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![SVN](https://img.shields.io/badge/SVN-809CC9?style=for-the-badge&logo=subversion&logoColor=white)

---

### Key Projects

#### [supershy42](https://github.com/supershy42)
> **MSA 기반의 실시간 웹 게임 서비스**   
Python, Django REST Framework, WebSocket, PostgreSQL, Redis  
2024.10 – 2025.01
- ##### [chat](https://github.com/supershy42/chat)
  > **실시간 채팅 관련 기능을 담당하는 서비스**  
  사용자 간의 채팅 관련 기능을 제공하는 Django 백엔드 서버입니다.   
WebSocket과 Redis를 활용하여 실시간 채팅 및 메시지 캐싱을 지원하고, 
PostgreSQL를 통해 채팅 이력을 관리합니다.  
마이크로 서비스로 네트워크를 통해 다른 서비스들과 소통하며,  
Docker 컨테이너 기반으로 독립적인 운영이 가능합니다.  
   
- ##### [game](https://github.com/supershy42/game)  
  > **게임 로비·대전·전적·토너먼트 기능을 담당하는 서비스**  
  WebSocket을 활용하여 게임 대기방 관리, 대기방 내 채팅, 실시간 게임 로직 처리,  
토너먼트 관리, 대전 기록 저장 및 조회 기능을 제공하는 Django 백엔드 서버입니다.  
Redis를 통한 게임 세션 상태 관리와 데이터 캐싱으로 빠른 응답성을 보장하며,  
PostgreSQL에 게임 결과 데이터를 저장합니다.  
마이크로 서비스로 네트워크를 통해 다른 서비스들과 소통하며,  
Docker 컨테이너 기반으로 독립적인 운영이 가능합니다.  

- ##### [user](https://github.com/supershy42/user)  
  > **사용자 인증·프로필·친구 관리를 담당하는 서비스**   
사용자 관리, 프로필 관리, 친구 요청/수락/거절/차단 기능을 제공하는 Django 백엔드 서버입니다.  
WebSocket과 Redis를 활용하여 실시간 개인 알림 시스템을 통해  
친구 요청, 게임 초대 등의 알림을 실시간으로 전달하며,  
PostgreSQL에 사용자 정보와 친구 관계 데이터를 저장합니다.   
마이크로 서비스로 네트워크를 통해 다른 서비스들과 소통하며,  
Docker 컨테이너 기반으로 독립적인 운영이 가능합니다.  

#### [Webserver](https://github.com/SPARTA42CLUB/Webserver)  
> **C++로 작성된 HTTP/1.1 구현 웹 서버**  
이벤트 큐 및 논블로킹 I/O를 활용하여 다중 클라이언트 처리를 지원합니다.  
GET, POST, UPDATE, DELETE 등의 HTTP 메소드와 chunk 전송, CGI 스크립트 실행 기능을 지원합니다.  
설정 파일을 통한 서버 옵션 커스터마이징이 가능하며,   
Docker 컨테이너 환경과 UNIX/BSD 계열 운영체제에서의 네이티브 실행을 지원합니다.  
2024.06 ~ 2024.07

#### [BoardPick-server](https://github.com/BoardPick/BoardPick-server)  
> **보드게임 추천 및 사용자 맞춤형 정보 제공 서비스**  
Spring Boot 기반의 보드게임 정보 서비스의 백엔드 서버입니다.  
다양한 보드게임의 상세 정보, 게임 룰, 관련 영상, 사용자 평점 및 랭킹 데이터를 제공합니다.  
사용자 맞춤형 보드게임 추천 알고리즘과 관심 게임 찜하기 기능을 통해 개인화된 서비스를 구현하며,  
Spring Security를 활용한 사용자 인증 및 권한 관리 시스템을 제공합니다.  
Amazon RDS 클라우드 데이터베이스와 연동되며,   
GitHub Actions를 통한 CI/CD 자동화로 Docker 컨테이너 기반의 Amazon EC2 배포를 지원합니다.  
2024.04 ~ 2024.06

#### [miniRT](https://github.com/seongmik-s-team/miniRT)  
>  **C언어로 구현된 레이트레이싱 3D 렌더링 엔진**  
벡터 및 행렬 연산을 통해 광선-객체 간의 교차점을 계산하여 사실적인 이미지를 생성합니다.  
뷰포트를 통한 카메라 이동, 회전, 확대/축소 기능을 지원하며,  
설정 파일을 통해 3D 객체, 카메라, 광원의 위치와 속성을 정의할 수 있습니다.  
Phong 조명 모델을 구현하여,  
ambient lighting, diffuse reflection, specular highlight, 그림자 효과를 제공합니다.  
2024.02 – 2024.03

#### [mini-shell](https://github.com/AhnJoonSung/)  
> **C언어로 구현된 경량화 Bash 쉘**   
명령어 파싱부터 프로세스 관리까지 쉘의 핵심 기능을 제공하는 터미널 인터프리터입니다.  
토큰화 및 어휘 분석을 통한 구문 오류 검사, 환경 변수 확장, 따옴표 처리 등의 문자열 처리 기능을 지원하며,  
fork()와 execve()를 활용한 프로세스 생성 및 관리를 통해 외부 프로그램 실행을 지원합니다.  
pipe()를 이용한 파이프라인 구성으로 프로세스 간 통신과, dup2()를 통한 입출력 리다이렉션과 heredoc 기능을 제공합니다.  
SIGINT, SIGQUIT 등의 시그널 핸들링과 종료 코드 관리($?)를 통해 안정적인 쉘 환경을 제공합니다.  
2023.11 – 2023.12

---

### 💡 Algorithm
[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=tjdtna01)](https://solved.ac/tjdtna01/)


<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=7FBCD2&height=150&section=footer"/>
</p>
