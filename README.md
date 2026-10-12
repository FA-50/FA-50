# 이정수 | JeongSu Lee

**Backend Developer | Java & Spring Boot | Spatial Data & GIS**

데이터를 활용해 사람들의 실생활에 가치를 더하는데 관심이 많은 신입 개발자입니다. 

이외에도 DevOps 분야에도 관심이 많아 관련 기술을 학습하여 블로그에 꾸준히 기록하고 개발에 적용하려고 노력하고 있습니다.

## Profile

| 항목 | 내용 |
| --- | --- |
| **Education** | 서울시립대학교 공간정보공학과 졸업 (2026.02) |
| **Birth** | 1998.03.04 |
| **Email** | [wjdtn747@naver.com](mailto:wjdtn747@naver.com) |
| **GitHub** | [github.com/FA-50](https://github.com/FA-50) |
| **Blog** | [velog.io/@wjdtn747](https://velog.io/@wjdtn747) |

---

## Tech Stack

**Backend**  
`Java` `Spring Boot` `Spring Framework` `Spring Security` `Spring Data JPA` `QueryDSL` `JWT` `OAuth2`

**Database & Infrastructure**  
`MySQL` `PostgreSQL` `Redis` `Docker` `Linux` `AWS EC2` `AWS VPC` `AWS Route 53` `AWS S3` `Apache Kafka` `GitHub Actions` `Nginx Proxy Manager`

**GIS & Data**  
`PostGIS` `pgRouting` `QGIS` `ArcGIS` `R` `GeoServer` `OpenLayers`

**Logging & Monitoring**  
`Elasticsearch` `Logstash` `Kibana` `Prometheus` `Grafana`

**Tools & Testing**  
`Git` `Postman` `Swagger` `JUnit 5` `Flyway`

---

## Projects

### 1. All 4 Runner | 최적 러닝코스 추천 지도 서비스

- **기간:** 2025.03 ~ 2025.06
- **구분:** 제39회 도시과학대학 공동작품전 졸업작품, 개인 프로젝트 (기여도 100%)
- **기술:** Java, Spring Boot, PostgreSQL, PostGIS, pgRouting, React, OpenLayers, GeoServer, QGIS, ArcGIS, R
- **개요:** 서울시 보행 네트워크를 활용해 경사도와 이동 환경을 고려한 러닝 경로를 추천하는 웹 지도 서비스

**주요 구현 내용**
- QGIS와 R을 활용해 서울시 도보 데이터를 전처리하고 약 118만 개 규모의 보행 네트워크를 재구축
- DEM과 고도 데이터를 가공해 경사도를 산출하고, 이를 경로탐색의 이동비용에 반영
- PostgreSQL의 pgRouting을 활용해 Dijkstra 기반 최적경로 탐색 REST API 구현
- React와 OpenLayers를 활용한 지도 화면 및 탐색 경로 시각화
- AWS EC2 기반 애플리케이션 배포

### 2. Dogether | 반려견 지역 커뮤니티 및 산책경로 추천 서비스

- **기간:** 2026.06.26 ~ 2026.08.28
- **구분:** 가상융합기술 아카데미, 5인 팀 프로젝트 (기여도 30%)
- **기술:** Java, Spring Boot, WebSocket, Apache Kafka, PostgreSQL, PostGIS, pgRouting, Redis, OpenLayers, QGIS, ArcGIS, R, Docker, AWS, GitHub Actions
- **개요:** 반려견 보호자를 위한 지역 커뮤니티와 공원, 경사도, 도로 특성을 반영한 산책경로 추천 기능 개발

**주요 구현 내용**
- OSM 및 공공데이터를 가공해 약 704만 개 규모의 전국 보행 네트워크 구축
- 공원, 경사도, 도로 특성을 이동비용에 반영하고 pgRouting 기반 A* 경로탐색 API 구현
- Kafka를 통한 비동기 경로탐색 처리와 WebSocket을 활용한 결과 전달 기능 구현
- BBOX로 탐색 범위를 제한하고, 쿼리플랜에서 확인한 Full Scan 문제를 공간 인덱스 적용과 쿼리 개선으로 해결
- **경로탐색 연산시간을 97.70초에서 1.17초로 약 98.8% 단축**
- AWS VPC, Docker, Nginx Proxy Manager, GitHub Actions를 활용한 배포 환경 및 자동화 파이프라인 구성

### 3. Asset-Box | 3D 에셋 공유 및 요청 기반 협업 플랫폼

- **기간:** 2026.05.26 ~ 2026.08.31
- **구분:** 가상융합기술 아카데미 백엔드 공동 프로젝트
- **기술:** Java 25, Spring Boot, Spring Data JPA, QueryDSL, Spring Security, JWT, OAuth2, MySQL, Redis, Apache Kafka, AWS S3, Docker, GitHub Actions, Nginx Proxy Manager, JUnit 5
- **개요:** TA(Technical Artist)와 개발자가 3D 에셋을 업로드, 공유, 요청 및 관리할 수 있는 협업 플랫폼

**주요 구현 내용**
- Kafka 기반 비동기 이메일 인증 처리 구조와 Consumer 서버 구현
- Spring Security 및 JWT 기반 로그인, 토큰 재발급, 인증 및 인가, 관리자 권한 분리 기능 구현
- Google, Naver OAuth2 로그인 및 서비스 토큰 발급 흐름 구현
- Swagger 기반 도메인별 API 문서화 및 JWT 인증 명세 구성
- GitHub Actions로 PR 테스트와 Docker 이미지 빌드, GHCR 배포 자동화
- Docker Compose와 AWS 인프라를 활용한 애플리케이션 실행 및 배포 환경 구성

### 4. h’our | 상품 주문 및 클래스 예약 커머스 플랫폼

- **기간:** 2026.06.29 ~ 2026.07.10
- **구분:** 가상융합기술 아카데미 백엔드 3차 프로젝트
- **기술:** Java 25, Spring Boot, Spring Data JPA, QueryDSL, Spring Security, JWT, PostgreSQL, Redis, AWS S3, Docker, GitHub Actions, AWS VPC, AWS EC2, Nginx Proxy Manager, JUnit 5
- **개요:** 상품 판매, 장바구니, 주문 및 결제, 배송 정책, 클래스 예약을 제공하는 커머스 플랫폼

**주요 구현 내용**
- Product, Cart, Order, ShippingPolicy, Purchase 도메인 개발
- 토스 결제 API를 연동한 상품 주문 및 결제 처리 흐름 구현
- Swagger를 통한 API 명세 관리와 인증 관련 문서화
- Dockerfile, Docker Compose를 활용한 PostgreSQL, Redis, Spring Boot 실행 환경 구성
- GitHub Actions 기반 테스트, Docker 이미지 빌드 및 GHCR 배포 자동화
- AWS VPC 및 EC2 환경에서 Public/Private Subnet, Bastion Host, NAT Gateway, Nginx Proxy Manager 기반 인프라 구성

### 5. 백엔드의 숲 | 게임 백엔드 API 서버

- **기간:** 2026.05.11 ~ 2026.06.09
- **구분:** 가상융합기술 아카데미, 2인 백엔드 팀 프로젝트 (기여도 55%)
- **기술:** Java, Spring Boot, Spring Security, OAuth2, Swagger, MySQL, Redis, Docker, Flyway, JUnit 5
- **개요:** 인증과 공유자원에 대한 동시성 제어를 포함한 게임 백엔드 API 서버 개발

**주요 구현 내용**
- Spring Security, OAuth2, Redis를 활용한 JWT 기반 인증 기능 구현
- Redis 분산락을 적용해 공유자원의 동시 접근을 제어하고 동시 요청 테스트로 검증
- Flyway를 도입해 개발 환경 간 데이터베이스 스키마 변경 이력 관리
- Swagger 기반 API 문서 작성 및 단위 테스트와 통합 테스트 수행
- Fetch Join을 활용한 연관 엔티티 조회 쿼리 작성

---

## Awards

| 수상 내역 | 시기 | 수상 | 주관 |
| --- | --- | --- | --- |
| 가상융합기술 아카데미 백엔드 과정 | 2026.08 | 우수교육생 | 한국전파진흥협회 |
| Urban Map & Archiving 데이터분석 프로그램 | 2024 | 장려상 | 서울시립대학교 도시사회학과 |
| 제1회 화성시 대학(원)생 데이터분석 공모전 | 2024 | 장려상 | 화성시 |

- **Urban Map & Archiving:** 서울 동북생활권 8개 구의 요식업 매출을 분석하고 QGIS, ArcGIS, R을 활용해 공간데이터를 전처리 및 분석
- **화성시 데이터분석 공모전:** 팀장으로 참여해 의료 접근성 및 수요 지수를 산출하고 공공의료원 최적 입지를 분석

---

## Experience

| 활동 | 기간 | 주요 내용 |
| --- | --- | --- |
| 가상융합기술 아카데미 | 2026.04 ~ 2026.08 | 백엔드 개발 과정 수료, 팀 프로젝트 수행 |
| 올포랜드 사업4그룹 산학실습인턴 | 2023.12 ~ 2024.02 | 정밀도로지도 관련 공간데이터 전처리 및 품질 기준에 따른 데이터 가공 |

---

## Education & Certifications

**Education**
- 서울시립대학교 공간정보공학과 졸업

**Certifications**
- 정보처리기사 (2025.12)
- SQLD (2024.06)
- OPIc IH (2026.01)
- 항공정비사 (2019.10)

---

## Activities & Others

**404 Not Found**
- 서울시립대학교 공간정보공학과 프로그래밍 소모임 (2023.03 ~ 2023.12)

**오늘도 달림**
- 대학 연합 러닝 동아리 활동
- Nike Run Club 기준 누적 약 3,700km 달리기 기록
- **2025 대구마라톤 완주:** 42.195km / **4:00:03**
