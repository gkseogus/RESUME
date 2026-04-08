# 한대현 (Han Dae Hyeon)

> **제로 베이스에서 운영까지 경험한 풀스택 개발자**

[![Gmail Badge](https://img.shields.io/badge/-fbznffldj998@naver.com-EA4335?style=flat-square&logo=Gmail&logoColor=white)](mailto:fbznffldj998@naver.com)
[![GitHub Badge](https://img.shields.io/badge/-gkseogus-181717?style=flat-square&logo=GitHub&logoColor=white)](https://github.com/gkseogus)

---

프론트, 백엔드 구분 없이 개발해온 **4년차 개발자**입니다.

- 요구사항 분석부터 설계, 개발, 테스트, 배포, 운영까지 **전체 개발 라이프사이클**을 경험했습니다.
- 이슈를 예측하고 최소한의 오류만을 허용하기 위해 **테스트 코드**를 중요시합니다.
- 혼자가 아닌 **팀원들과 함께** 일하는 것을 중요시합니다.

---

## Tech Stack

#### Core
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Redux](https://img.shields.io/badge/-Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

#### Also Working With
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MongoDB](https://img.shields.io/badge/-MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

---

## Experience

### 하이퍼스타 주식회사 (Hyperstar Inc.)
`2025.10 - 2026.02` | 정규직 | 개발팀

#### 인플루언서 마케팅 SaaS 플랫폼 구축
> React, TypeScript, Zustand, TanStack Query, FastAPI, PostgreSQL, AWS, Vercel, Stripe

**제로 베이스에서 운영까지 전체 개발 주도**

<details>
<summary><b>Frontend</b></summary>

- React + TypeScript 기반 SPA 아키텍처 설계 및 구현
- Zustand + TanStack Query를 활용한 상태 관리 체계 구축
- 다국어 지원 시스템 구현 (EN/KO/JP)
- Stripe 결제 시스템 연동 (크레딧 구매, 구독 플랜)
- 결제 중복 방지 로직 구현 (idempotency key, ref guard)
</details>

<details>
<summary><b>Backend</b></summary>

- FastAPI 기반 RESTful API 서버 설계 및 구현 (엔드포인트 80개+)
- PostgreSQL 데이터베이스 스키마 설계 (테이블 50개+)
- Stripe Webhook 결제 처리 시스템 구축 (재시도 로직, 중복 처리 방지)
- JWT 기반 인증/인가 시스템 구현
- Google OAuth 소셜 로그인 연동
</details>

<details>
<summary><b>Data Pipeline</b></summary>

- TikTok 인플루언서 데이터 크롤링 시스템 구축
- Chrome Extension 기반 실시간 데이터 수집 (팔로워, 영상 통계)
- AWS Lambda를 활용한 서버리스 데이터 처리
- 10만+ 인플루언서 데이터 수집 및 관리
</details>

<details>
<summary><b>Infra & DevOps</b></summary>

- AWS (RDS, S3, Lambda, CloudWatch) 인프라 구축
- Vercel 기반 프론트엔드 CI/CD 파이프라인 구성
- GitHub Actions 기반 자동 배포 환경 구축
- Nginx + EC2 기반 백엔드 서버 운영
- SES를 통한 메일 송수신 시스템 구축
</details>

**성과**
- 제로 베이스에서 **2개월 만에 MVP 출시**
- MAU 100+ 서비스 안정적 운영
- 결제 시스템 도입으로 매출 발생 기반 마련
- **99.9% 서비스 가용성** 유지

---

### 더매니저 주식회사
`2025.03 - 2025.09` | 계약직 | 개발팀

#### 테이블매니저 APP 유지보수
> Flutter, Dart

- 플러터 기반 앱 유지보수를 통해 운영 개선 사항 및 매장 불편 요소 최소화
- 소스코드 내 잘못된 렌더링 참조를 리팩토링하여 불필요한 렌더링 제거 및 성능 최적화
- 문의사항 챗봇 크래시 이슈 수정 → 앱 크래시 발생률 **3% 미만**으로 감소
- UX/UI 구조 개선을 통해 사용자 경험 향상

#### 더한옥 주문 시스템 구축
> FastAPI, MySQL, MongoDB, AWS (RDS, CloudWatch, Lambda, DynamoDB)

- AWS Lambda 기반 주문 데이터 파이프라인 신규 설계 및 구축
- 수동 처리 대비 데이터 누락률 **5% → 0%**로 개선
- 주문 데이터 응답 속도 **2초 → 1.2초** (40% 단축)
- 50개 테스트 케이스 기준 결함률 0% 달성

#### 학교방문예약시스템 유지보수
> Node.js, MongoDB, AWS (RDS, CloudWatch, Lambda)

- 긴급 이슈 평균 2시간 내 해결, **SLA 100%** 준수
- 월 평균 고객센터 문의 **200건 → 130건** (35% 감소)
- CloudWatch 알람 자동화로 이슈 인지 시간 **30분 → 18분** 단축

#### 티켓매니저 바코드 서버/웹 구축
> FastAPI, React, TypeScript, AWS (RDS, API Gateway, EC2, Route53), Nginx

- 주문 건별 바코드 생성 및 키오스크 인식 서비스 구축
- 네이버, 쿠팡, 11번가, 휘닉스파크, 인터파크 등 **5개 채널 연동**
- 일 평균 5,000건 바코드 발급, 월 15만 건 처리 중 **오류율 0.02%** 유지
- Certbot + Crontab SSL 인증서 자동 갱신, 서비스 무중단 운영

---

### 주식회사 메멘토에이아이
`2024.08 - 2025.01` | 정규직 | 개발팀

#### 뮤즈, 샤인빔 피부과 CRM / MIRA / ADMIN 서버 구축
> FastAPI, MySQL, AWS (RDS, API Gateway, CloudWatch, S3, ECS), Alembic, Terraform

<details>
<summary><b>성능 개선</b></summary>

- 동시 예약 시 deadlock을 낙관적 락(Optimistic Lock)으로 전환 → **동시 처리량 3배 향상**
- 고객 조회 쿼리 속도 **1.3초 → 0.6초**
- 예약 목록 조회 API 응답 시간 **1.5초 → 0.63초** (58% 향상, N+1 쿼리 제거)
- Sentry를 통한 실시간 에러 모니터링 체계 구축
</details>

<details>
<summary><b>CRM 핵심 기능</b></summary>

- 예약부터 시술 완료까지 전체 프로세스 백엔드 설계 및 구현
- 멀티 채널(홈페이지, MIRA 앱) 예약 시스템 통합 및 실시간 동기화
- 예약 관리 / 회원 관리 / 진료기록부 / 전자서명 및 동의서 / 알림톡
</details>

<details>
<summary><b>Infrastructure</b></summary>

- **Terraform**을 활용한 Infrastructure as Code (멀티 환경 관리)
- ECS 기반 마이크로 서비스 아키텍처 배포 환경 구성
- Alembic을 통한 데이터베이스 마이그레이션 관리
- 멀티 파트 + S3 활용 대용량 문서 저장 시스템 구축
</details>

---

### 주식회사 퀀터스테크놀로지스
`2024.02 - 2024.08` | 정규직 | 개발팀

#### 실전투자 백오피스 구축 (단독 프로젝트)
> TypeScript, React, Recoil, Emotion-Styled, FastAPI, MySQL

- Celery Beat 스케줄러로 미장/국장 개장 전 자동 데이터 정규화, 일 평균 **50만 건** 처리
- 포트폴리오, 주가, 손익 데이터 시각화 UX/UI 설계 및 구축

#### 알파파인더 프론트 구축 (단독 프로젝트)
> TypeScript, React, Recoil, Emotion-Styled, Chart.JS

- 실시간 주가 데이터 스트리밍 및 AI 기반 뉴스 매칭 시스템 구현
- Virtual Scroll 구현으로 10,000건+ 데이터 **60fps** 유지 렌더링
- 초기 로딩 시간 **4초 → 2초** (50% 단축)
- 드래그 앤 드롭 차트 데이터 병합 및 비교 분석 기능

---

### 진진시스템(주)
`2022.08 - 2024.02` | 정규직 | 시스템개발부

#### 대한체육회 하키/아이스하키 참가신청, 정보제공 사이트 최신화
> Java, JSP, jQuery, CSS, Oracle DB, Mybatis

- 참가 신청 **7단계 → 4단계**로 프로세스 개선
- 참가 신청, 정보제공 사이트 통합 (단일 로그인)
- 와일드카드 시스템 도입

#### 대한체육회 레슬링 참가신청/대회운영 시스템 유지보수
> Java, JSP, PowerBuilder, MariaDB

- 협회 핫라인 구축 후 실시간 문제점 파악 및 해결

#### 전국체육대회 사이트 데이터 검토 및 웹 QA
- 쿼리 레벨 코드 검증 (인덱스, N+1 Query 등)
- 데드락 요인 확인 및 화면 설계서 기반 통합 테스트

---

### 에이치나인
`2022.01 - 2022.07` | 인턴 | R&D

#### LG 경영연구원 / 리서치 인프라 웹 페이지 QA
> Jira, GitHub, Teams, Google Sheets

- 200개+ 테스트 케이스 작성 및 실행
- QA 성공률 목표 95% → 실제 **99% 달성**
- 1차/2차 개편 모두 **무장애 오픈**

---

## Education

**한림대학교** | 빅데이터 전공 | `2019.03 - 2023.02` 졸업

---

## Awards & Activities

| 연도 | 내용 |
|------|------|
| 2023 | **나만코** B2B 명함 관리 SaaS 플랫폼 프론트엔드 총괄 (팀원 3명) |
| 2021 | **추계종합학술발표회** 우수논문 선정, 장려상 수상 |
| 2021 | **오픈소스SW 개발 공모전** 딥러닝 기반 사물인식 모델 구축 (교내 1등) |
| 2021 | **오소리 동아리 회장** - 딥러닝/머신러닝 논문 탐구 및 실생활 적용 |
| 2020 | **HUS 동아리 회장** - 신입생 대상 Python/Pygame 멘토링 |

---

## Links

| | |
|---|---|
| **뮤즈강남 홈페이지** | https://gangnam.museclinic.co.kr/ko |
| **대한체육회 하키 참가신청** | https://app.sports.or.kr/app_ih/app/main.do |
| **대한체육회 레슬링 참가신청** | https://app.sports.or.kr/app_wr/app/main.do |
| **추계종합학술발표회 논문** | [DBpia 링크](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11023003) |
| **GitHub** | https://github.com/gkseogus |

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=gkseogus&show_icons=true&theme=default&hide_border=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gkseogus&layout=compact&hide_border=true" height="165" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=gkseogus&theme=default" />
</p>
