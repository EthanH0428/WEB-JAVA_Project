# 🏠 부동산 임장(방문) 기록 다이어리

관심 있는 부동산 단지를 직접 방문(임장)하고, 현장의 상세 정보와 사진, 체크리스트 기반의 평가를 체계적으로 기록·관리하는 웹서비스입니다.

---

## 📌 기획 배경
부동산 임장 시 메모장, 사진첩, 지도 앱 등에 흩어지기 쉬운 현장 정보를 한곳에 모아 관리하고, 정량적인 체크리스트 평가를 통해 객관적인 단지 비교를 돕기 위해 기획했습니다.

## ✨ 주요 기능

### 1. 회원 및 보안 관리
* 회원가입, 로그인 및 로그아웃 (세션 기반 인증)
* 비밀번호 암호화 및 비로그인 사용자의 다이어리 접근 제어

### 2. 임장 대상 단지 관리
* 관심 단지 등록, 조회, 수정 및 삭제 (CRUD)
* 관심 단지 북마크 및 목록 검색·필터링

### 3. 임장 기록(다이어리) 작성 및 평가
* 방문 일자별 임장 기록 작성, 상세 조회, 수정 및 삭제
* 현장 사진 업로드 및 상세 메모 첨부
* 항목별 체크리스트 기반 종합 평점 산출

### 4. 일정 및 부가 기능
* 지도 연동을 통한 단지 위치 확인 및 임장 일정 관리
* 방문 예정일 확인 및 알림 관리

---

## 🛠️ 사용 기술 및 개발 환경

### 사용 기술
* Java
* JSP / Servlet
* JDBC
* Oracle Database
* HTML5 / CSS3 / JavaScript

### 개발 환경
* **WAS:** Apache Tomcat
* **IDE:** Eclipse, VS Code
* **VCS:** Git, GitHub

---

## 📂 프로젝트 문서

| 위치 | 파일명 | 용도 | 이슈번호 |
| --- | --- | --- | --- |
| [guides/](guides/commit-policy.md) | commit-policy.md | 커밋 메시지 정책 | - |
| [docs/00_SRS/](docs/00_SRS/요구사항명세서_기능명세서_v.1.xlsx) | 요구사항명세서_기능명세서_v.1.xlsx | 요구사항 및 기능명세서 | [#1](https://github.com/EthanH0428/WEB-JAVA_Project/issues/1) |
| [docs/01_UseCase/](docs/01_UseCase/UseCase.drawio.png) | UseCase.drawio.png | 유스케이스 다이어그램 | [#2](https://github.com/EthanH0428/WEB-JAVA_Project/issues/2) |
| [docs/02_ERD/](docs/02_ERD/ERD.png) | ERD.png | 데이터베이스 모델링 | [#3](https://github.com/EthanH0428/WEB-JAVA_Project/issues/3) |

---

## 📁 디렉토리 구조

```text
WEB-JAVA_Project/
├── docs/
│   ├── 00_SRS/          # 요구사항 및 기능명세서
│   ├── 01_UseCase/      # 유스케이스 다이어그램
│   └── 02_ERD/          # 데이터베이스 ERD
├── guides/
│   └── commit-policy.md # 커밋 컨벤션 가이드
├── src/                 # Java 소스코드 (Servlet, DAO, DTO 등)
├── webapp/              # JSP, CSS, JS, 이미지 리소스
├── .gitignore
└── README.md
```

---

## 🚦 진행 상태

현재 요구사항과 기능을 설계하고 있습니다.

* [x] 프로젝트 초기 세팅 및 커밋 정책 수립
* [x] 요구사항 및 기능명세서 작성 (`v.1`)
* [ ] 유스케이스 다이어그램 작성
* [ ] 데이터베이스 ERD 설계 및 테이블 생성
* [ ] 회원 기능(가입/로그인/로그아웃) 구현
* [ ] 임장 기록 CRUD 및 체크리스트 기능 구현
* [ ] UI/UX 개선 및 최종 테스트