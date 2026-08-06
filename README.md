# 이정수 JeongSu Lee

---
### Education
서울시립대학교 공간정보공학과 졸업 ( 2026.02 )

### Birth.

1998년 3월 4일 

### E-Mail.

wjdtn747@naver.com

### Blog 

📁 https://velog.io/@wjdtn747

---

# Introduce.

복잡한 데이터 내에서 최선의 길을 찾아 가치를 창출하고 사람들의 실생활 개선에 이바지하고 싶은 개발자입니다.

---

# Tool & Skills

#### `Backend` :

- `Java` , `Spring Framework` , `Spring Security` , `Spring Data JPA` , `QueryDSL` , `R`

#### `DB & Infra` :

- `MySQL` , `PostgreSQL` , `Redis`
- `Docker` , `Linux` , `Nginx Proxy Manager` , `AWS EC2` , `AWS VPC` , `AWS Route 53` , `Apache Kafka` , `Github Actions`

#### `Logging & Monitoring` :

- `Elastic Search` , `Kibana` , `Logstash` , `Prometheus` , `Graphana`

 

#### `Tool` :

- `Git` , `Postman` , `Swagger` , `JUnit 5` ,  `Flyway` , `QGIS` , `ArcGIS`

---

# Projects.

상세 프로젝트 내역

---

### 3D 에셋 공유 및 요청 기반 협업 포털

프로젝트명 : `Asset-box` 

- 가상융합기술아카데미 백엔드 공동 프로젝트
- 일정 : 2026. 05. 26 ~ 2026. 08. 31
- 기술스택 :
    
    Java 25 , Spring Boot 4.0.6 , Spring Data JPA , QueryDSL , Spring Security , JWT , OAuth2 Client ,   Swagger , MySQL , Redis , AWS S3 , H2 DB , Docker , GitHub Actions , Nginx Proxy Manager, JUnit 5 , Swagger , Postman
    
- 개요 : TA(Technical Artist)와 개발자가 협업하여 3D 에셋을 업로드, 공유, 요청, 관리할 수 있는 웹 기반 에셋 공유 플랫폼 구축
- 담당 분야
    - Kafka 를 활용한 비동기 구조 구축 및 이메일 인증 시스템 구축
    - 회원 도메인을 기반으로 Spring Security와 JWT를 활용하여 로그인, 토큰 재발급, 인증/인가, 관리자 권한 분리 기능 구현
    - Google/Naver OAuth2 로그인 흐름을 구성하고, 인증 성공 후 서비스 토큰을 발급하는 구조 설계
    - Swagger를 활용하여 도메인별 API 문서 그룹화 및 JWT 인증 문서화 적용
    - GitHub Actions를 통해 dev 브랜치 테스트 자동화, main 브랜치 Docker 이미지 빌드 및 GHCR 배포 파이프라인 구성
    - Docker Compose로 MySQL, Redis, 백엔드, 프론트엔드, Nginx Proxy Manager를 포함한 AWS VPC를 통한 운영 배포 환경 구성

### 온라인 상품 주문 및 클래스 예약 커머스 플랫폼

프로젝트명 : `h’our`

- 가상융합기술아카데미 백엔드 3차 프로젝트
- 일정 : 2026. 06. 29 ~ 2026. 07. 10
- 기술스택 :
    - Java 25, Spring Boot 4.0.7, Spring Data JPA, QueryDSL, Spring Security, JWT, OAuth2 Client,  Swagger, PostgreSQL, Redis, AWS S3, H2 DB, Docker, GitHub Actions, AWS VPC, AWS EC2, Nginx Proxy Manager, JUnit 5, Swagger, Postman
- 개요 : 상품 판매, 장바구니, 주문/결제, 배송 정책, 클래스 예약 기능을 제공하는 웹 기반 커머스 및 예약 플랫폼
- 담당 분야
    - Product, Cart, Order, ShippingPolicy , Purchase 도메인을 담당하여 토스 결제 API를 기반으로 상품 주문 시 결제기능까지 결제 흐름 구현
    - Swagger를 활용하여 도메인별 API 문서 그룹화 및 JWT 인증 문서화 적용
    - Dockerfile과 Docker Compose를 구성하여 PostgreSQL, Redis, Spring Boot 애플리케이션 실행 환경 구성
    - GitHub Actions 기반 CI/CD 파이프라인을 구성하여 PR 테스트 자동화, main 브랜치 Docker 이미지 빌드 및 GHCR 배포 흐름 구축
    - AWS VPC와 EC2를 활용하여 운영 배포 환경을 구성하고, Public/Private Subnet, Bastion Host, NAT Gateway, NginxProxy Manager 기반 인프라 설계

### 최적 러닝코스를 추천하는 웹 기반 지도어플리케이션

프로젝트명: `All 4 Runner`


- 제 39회 도시과학대학 공동작품전 : 졸업작품 프로젝트
- 일정 : 2025. 03 ~ 2025. 06
- 기술스택 :
    
     Java 17, Spring Boot 3.5.7, Spring Data JPA, QueryDSL, Spring Security ( JWT ), OAuth, PostgreSQL, PostGIS, pgrouting, React, OpenLayers , GeoServer
    
- 개요 : 서울 시내 방해물을 최소화하면서 경사를 최소로 하는 러닝코스를 제공하는 어플리케이션 개발
- 담당 분야
    - 경로데이터 확보 및 QGIS, R을 활용하여 경로데이터 전처리
    - React를 활용하여 지도 서비스 구현 및 OpenLayers 라이브러리를 통해 경로 시각화
    - Spring Framework와 PostgreSQL의 pgrouting 기능을 통해 최적경로 반환 REST API 구현
    - AWS EC2를 프로비저닝하여 배포
    

---

# Awards.

---

| 대회명 | 기간 | 상 | 기관 |
| --- | --- | --- | --- |
| 서울신용보증재단 Urban Map&Archiving : 데이터분석중심 프로그램 | 2024-11-17 ~ 2024-11-24 | 장려상 | 서울시립대학교 도시사회학과 |
| 제 1회 화성시 대학(원)생 데이터분석 공모전 | 2024.10.07 ~ 2024.11.08 | 장려상 | 화성시 |

---

# Experience

---

| 회사명 | 직급 | 기간 | 비고 |
| --- | --- | --- | --- |
| 가상융합기술 아카데미 | 백엔드 | 2026/04/06 ~ 2026/08/31 |  |
| 올포랜드 | 사업4그룹 (산학인턴) | 2023/12/26 ~ 2024/02/23 ( 2개월 ) | 데이터 가공 및 사무 보조 |

---

# Others.

---

## 404 Not Found

- 서울시립대학교 공간정보공학과 프로그래밍 소모임
- 활동기간 ( 2023. 03 ~ 2023. 12 )

### 오늘도 달림

인스타그램 링크

- 대학 연합 러닝 동아리
- 활동기간 ( 2024. 02 ~ )

### 2025 대구마라톤 완주

- 42.195km / 4:00:03
