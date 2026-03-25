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
├── style.css               # 공통 CSS (변수·리셋·베이스)
├── index.html              # 메인 포털 (사이드바 + iframe 구조)
├── placeholder.html        # 준비 중 페이지 (미완성 링크 클릭 시 표시)
├── news-template.html      # 뉴스 페이지 템플릿 (새 주차 작성 시 복사)
├── news-week03.html        # 3주차 생명과학 뉴스
├── week3_article01.png     # 3주차 기사 이미지 01
├── week3_article02.png     # 3주차 기사 이미지 02
├── week3_article03.png     # 3주차 기사 이미지 03
└── week3_article04.png     # 3주차 기사 이미지 04
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

## 새 주차 뉴스 페이지 추가 방법

1. `news-template.html`을 복사하여 `news-weekNN.html`로 저장
2. `★` 주석이 붙은 항목을 해당 주차 내용으로 수정
3. 이미지 파일을 아래 규칙에 맞게 저장 후 같은 폴더에 업로드
4. `index.html` 사이드바에 새 항목 추가

### 이미지 파일명 규칙

```
weekN_article01.png
weekN_article02.png
weekN_article03.png
weekN_article04.png
```

예시: 4주차 → `week4_article01.png`, `week4_article02.png` ...

---

## 업데이트 이력

| 날짜 | 내용 |
|------|------|
| 2026-03-24 | 최초 배포 — `index.html`, `news-week03.html`, 이미지 4종 |
| 2026-03-25 | 가독성 개선 — 폰트 크기·웨이트 전반 조정 |
| 2026-03-25 | 구조 개선 — `style.css` 공통 분리, `news-template.html`, `placeholder.html` 추가 |

---

## 기술 스택

- 순수 HTML / CSS / JavaScript (빌드 도구 없음)
- Google Fonts: Playfair Display · Noto Serif KR · Noto Sans KR · DM Mono
- GitHub Pages 배포
