# 이해와 가치실현을 위한 생명과학

**2026학년도 1학기 교양필수 강의 포털**
담당교수: 조운석 · woonseok.cho@gmail.com

---

## 개요

생명과학의 핵심 개념을 일상과 연결하고, 과학적 사고로 건강·환경·생명 관련 정보를 비판적으로 평가하는 능력을 기르는 강의 자료 게시용 웹서비스입니다.

- **교과목**: 이해와 가치실현을 위한 생명과학
- **대상**: 3학년 교양필수
- **평가**: 기말시험 50% · 과제 30% · 수업참여 10% · 출석 10%
- **주교재**: 생활 속의 생명과학 제5판 (바이오사이언스, 2016)
- **부교재**: 생명 생물의 과학 제12판 (라이프사이언스)

---

## 파일 구조

```
26BioSci_BNUE/
├── index.html              # 메인 포털 (사이드바 + iframe 구조)
├── news-week03.html        # 3주차 생명과학 뉴스
├── week3_article01.png     # 3주차 기사 이미지
├── week3_article02.png
├── week3_article03.png
├── week3_article04.png
└── README.md
```

### 추가 예정 파일

| 파일명 | 내용 | 상태 |
|--------|------|------|
| `syllabus.html` | 강의계획서 | 예정 |
| `week01.html` | 1주차 — 과학적 방법론 | 예정 |
| `week02.html` | 2주차 — 세포와 생명 | 예정 |
| `week03.html` | 3주차 — 유전과 단백질 | 예정 |
| `week04.html` | 4주차 — 진화와 다양성 | 예정 |
| `assignment.html` | 주차 사전 과제 | 예정 |
| `discussion.html` | 유사과학 토의 자료 | 예정 |
| `reference.html` | 강의 보조자료 | 예정 |
| `links.html` | 유용한 링크 모음 | 예정 |
| `news-week01.html` | 1주차 생명과학 뉴스 | 예정 |
| `news-week02.html` | 2주차 생명과학 뉴스 | 예정 |

---

## 업데이트 이력

| 날짜 | 내용 |
|------|------|
| 2026-03-24 | 최초 배포 — `index.html`, `news-week03.html`, 이미지 4종 |
| 2026-03-25 | 가독성 개선 — 폰트 크기·웨이트 전반 조정 |

---

## 차후 개선 계획

### 1. 공통 CSS 분리
현재 각 HTML 파일에 스타일이 내장(inline)되어 있어 디자인 변경 시 파일마다 개별 수정이 필요합니다.
`style.css` 하나로 공통 스타일을 분리하면 전체 디자인을 일괄 변경할 수 있습니다.

```
style.css  ← 공통 CSS (variables, typography, layout, components)
```

### 2. 뉴스 페이지 템플릿화
`news-template.html`을 기준 파일로 만들고, 매 주차마다 복사·수정하는 방식으로 일관된 디자인을 유지합니다.

### 3. 미완성 페이지 처리
현재 링크는 있으나 파일이 없는 페이지(week01~04 등) 클릭 시 흰 화면이 표시됩니다.
공통 `placeholder.html`("준비 중" 안내 페이지)을 만들고 임시 연결합니다.

### 4. 이미지 네이밍 규칙 통일
현재 `week3_article01.png` / `article2.png` 등 혼재되어 있습니다.
`weekN_articleN.png` 규칙으로 통일합니다.

---

## 기술 스택

- 순수 HTML / CSS / JavaScript (빌드 도구 없음)
- Google Fonts: Playfair Display · Noto Serif KR · Noto Sans KR · DM Mono
- GitHub Pages 배포
