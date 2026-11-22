# 🅿️ parking-lot-management

> 2026-2학기 소프트웨어공학 기말 팀 프로젝트 — **주차장 관리 시스템** (Java 콘솔 애플리케이션)

차량의 **입차 → 주차면 자동 배정 → 출차 → 요금 정산 → 이력·매출 관리**까지 처리하는 주차장 관리 프로그램입니다.

---

## 👥 Team

| 이름 | GitHub | 담당 |
|---|---|---|
| 김동형 | [@dongbro-png](https://github.com/dongbro-png) | Frontend — 콘솔 UI, 입력 처리, 화면 출력 |
| 박찬영 | [@newsa12](https://github.com/newsa12) | Backend — 도메인 모델, 비즈니스 로직, 데이터 저장 |

---

## 📄 Documents

| 문서 | 설명 | 상태 |
|---|---|---|
| [프로젝트 제안서](docs/PROPOSAL.md) | 주제, 구현 기능, 역할 분담, 일정 | ✅ 제출 |
| 작업 명세서 (SRS) | 기능 명세, 데이터 규격, 핵심 인터페이스, UML | 🚧 작성 중 (1차 마감 11/29) |
| 최종 발표 자료 | 아키텍처, 핵심 인터페이스, 실행 데모 | ⏳ 예정 (12/8 제출, 12/9 발표) |

---

## ✨ Features

- **입차 처리** — 차종에 맞는 빈 주차면 자동 배정
- **출차·요금 정산** — 주차 시간·차종·할인 조건에 따른 요금 계산과 영수증 출력
- **차량 조회** — 차량번호로 위치·입차 시각·예상 요금 조회
- **주차 현황** — 층별 주차면 상태를 텍스트 맵으로 표시
- **정기권 관리** — 정기권 차량 등록·해지, 출차 시 요금 면제
- **매출 리포트** — 일별·차종별 매출 집계
- **데이터 저장** — CSV 파일로 저장하고 다시 불러오기

---

## 🛠 Tech Stack

- **Language:** Java (JDK 17+)
- **IDE:** Eclipse / IntelliJ IDEA
- **Collaboration:** GitHub (Issues, Pull Request)

---

## 🚀 How to Run

> 구현이 진행되면 실행 방법과 메뉴별 사용 설명을 이 섹션에 추가합니다.

```bash
# (예정) 소스 컴파일 및 실행
javac -d bin $(find src -name "*.java")
java -cp bin Main
```

---

## 🤝 Collaboration Rules

- **브랜치:** `main` (제출용) ← `develop` (통합) ← `feature/기능명` (개인 작업)
- **코드 반영:** 기능 단위 Pull Request → 상대 팀원 리뷰 후 병합
- **커밋 메시지:** `feat:` 기능 추가 · `fix:` 버그 수정 · `docs:` 문서 · `refactor:` 구조 개선
