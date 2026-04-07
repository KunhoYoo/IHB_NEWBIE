# IHB_NEWBIE

https://kunhoyoo.github.io/IHB_NEWBIE/

# 📖 신입 교육 백과사전 (Newbie Knowledge Base)

신입 직원을 위한 **업무 지식 관리 웹 애플리케이션**입니다.  
펌뱅킹, 네트워크, 업무 용어, 장애 대응 사례 등을 한 곳에서 검색하고 관리할 수 있습니다.

---

## 🚀 주요 기능

### 🔍 1. 실시간 검색
- 키워드 기반 빠른 검색
- 제목 / 설명 / 태그까지 전체 검색 지원
- `Ctrl + F` → 검색창 포커스 기능 제공

---

### 📂 2. 카테고리 필터
- 📚 전체 보기
- 🏦 펌뱅킹
- 🌐 네트워크
- 📝 업무 용어
- 🛠️ 대응 사례

카테고리별 개수 자동 집계 및 표시

---

### 📊 3. 통계 대시보드
- 각 카테고리별 데이터 수 표시
- 클릭 시 필터링 동작

---

### 📄 4. 아코디언 형태 지식 카드
- 카드 클릭 시 상세 정보 확장
- 한 번에 하나만 열리는 구조
- 포함 정보:
  - 설명
  - 핵심 정보 (Key-Value)
  - 처리 절차 (Step-by-step)
  - 경고 / 안내 메시지
  - 태그

---

### ✏️ 5. 관리자 기능 (Admin Only)
- 항목 추가
- 항목 수정
- 항목 삭제
- Rich Text Editor 지원 (굵게, 리스트 등)

---

### 🔐 6. 로그인 기능

| 역할   | 권한        |
|--------|------------|
| admin  | 전체 기능 사용 |
| newbie | 조회 전용     |

---

### ⏰ 7. 실시간 시계
- 초 단위 현재 시간 표시

---

## 🧩 기술 스택

- **Frontend**
  - HTML5
  - CSS3 (Custom Design System)
  - Vanilla JavaScript

- **Backend (BaaS)**
  - Firebase Realtime Database

- **기타**
  - Google Fonts (Pretendard)
  - Firebase SDK (v10)
