# 위캐리 미팅 자료실

현재 자료는 **컨설팅 보고서 v1.29 · 개발 PRD v2.0 · 1차 납품서**입니다. PRD v2.0과 납품서 상태는 **1차 납품본(v2.0.0-alpha.2), 실기 재확인 전**입니다(2026-11-14).

[자료실 첫 화면](index.html)에서 현재 자료 3개를 먼저 열고, 이전 조사·설계·제안·미팅 기록은 아래의 이전 자료에서 확인합니다. 기존 공개 파일과 주소는 보존합니다. 문서 게시·설치 파일 제공은 제품 실기 재시험이나 고객 인수 완료를 뜻하지 않습니다.

## 현재 자료

### 컨설팅 보고서 v1.29

업무 흐름·납품 기능·기대효과·미팅 안건을 다룬 기존 보고서입니다. 당시 내용은 그대로 유지하며 현재 개발 구성·납품 상태는 PRD v2.0과 납품서를 기준으로 읽습니다.

- [웹에서 보기](report.html)
- [PDF 다운로드](pdf/report-v1.29.pdf)
- [Markdown 원문](report-v1.29.md)

### 개발 PRD v2.0

스킬·공식 연결·Google 검색광고 확장 구성, 사용자 흐름, 기능 요구와 하드 규칙, 매체별 동작, 설정값 출처, 검증 상태와 남은 일을 정리했습니다. 기준은 wecarry-ax-v2 main `7df6ed9`의 계획·결정 1~28·납품 유의사항·1차 납품 기록·스킬 규칙입니다.

- [웹에서 보기](prd-v2.0.html)
- [Markdown 원문](prd-v2.0.md)
- 웹 페이지의 **인쇄 / PDF** 기능으로 인쇄할 수 있습니다. 이번 개정에는 별도 PDF 파일이 포함되지 않았습니다.

### 1차 납품서

관리자 설치·마케터 사용·유의사항·위캐리 준비 체크리스트·미팅 안건입니다. Drive 주소가 반영된 main의 안내 HTML·Markdown을 그대로 복사했습니다.

- [웹에서 보기](delivery.html) — 자료실 보관본, 만료일 없음
- [납품 파일 폴더](https://drive.google.com/drive/folders/1hU0ZCut5hYmS2USXDLfeIFpDzRS441gC?usp=sharing)
- [공개 아티팩트](https://share.onorca.dev/a/u1rGSYFPplj5) — **2026-12-14 만료**
- [Markdown 원문](delivery.md)

## 이전 자료

### 개발 PRD v1.12

**v1(설치 프로그램 방식) 기준, v2.0으로 대체**. 실행 서버·데이터 계약·세 매체 API·복구·인수 기준과 6주 개발 계획을 담은 보존 기록입니다.

- [이전 웹 보기](prd.html)
- [PDF](pdf/prd-v1.12.pdf)
- [Markdown](prd-v1.12.md)

### Notion 광고 운영 관리 제안서 v1.1

기존 업무 유지·실제 작성 위치·평소 요청과 변경 요청·자동 기록 범위를 다룹니다. 평소 요청에는 추가 작성이 없고 기존 정보에서 알 수 없는 변경만 비고·본문에 보충하는 개정본입니다. 새 필수 속성·선택표·수동 확정본·승인 단계는 기본안에서 제외했으며 실제 Notion 구조·운영 시트·광고 데이터는 변경하지 않았습니다.

- [웹](notion-management.html) · [PDF](pdf/notion-management-v1.1.pdf) · [Markdown](notion-management-v1.1.md)
- [내장 폰트 라이선스](notion-management-font-licenses.txt)
- 이전 v1.0 [Markdown](notion-management-v1.0.md)·[PDF](pdf/notion-management-v1.0.pdf)도 보존합니다. 이전안의 신규 작성표·승인 속성 제안은 v1.1로 대체됩니다.

### AI 리서치 v1.0

- [웹](research.html) · [PDF](pdf/research-v1.0.pdf) · [Markdown](research.md)

### 설문 원문 응답

46문항·48개 필드·4명의 응답입니다. 실명 치환 R1~R4와 기존 자유서술·공개 범위를 유지합니다.

- [웹](survey.html) · [PDF](pdf/survey-original.pdf) · [CSV](survey-original.csv)

### 10/29 미팅노트

- [웹](meeting-notes-2026-10-29.html) · [Markdown](meeting-notes-2026-10-29.md)

### 전체 ZIP · 이전 묶음

- [보고서 v1.29·PRD v1.12 전체 ZIP](wecarry-meeting-v1.29-prd-v1.12.zip)

이 ZIP은 이전 자료 묶음이며 PRD v2.0과 alpha.2 설치 파일을 포함하지 않습니다. 새 자료와 설치 파일은 위의 현재 자료에서 받습니다.

## 이전 개정 기록

- 2026-10-29 보고서 v1.28: 1절 끝에 다섯 요청 유형과 개발 중 최종 검증 안내 추가, 제목·PDF 표지의 버전 표시.
- 같은 날 PRD v1.12: 요청 묶음과 하위 작업 연결, 실행 계층의 분해·호출·집계, 브랜드 격리와 부분 실패 시 정상 작업 보존, VT02·VT05·VT16 보완. 실제 광고 실행·런타임 구현·Notion 변경을 뜻하지 않음.
- 2026-10-30 보고서 v1.29: 요청에 따라 7절의 지원 조건 기재 내용 삭제. 해당 보고서와 기존 파일은 이번 개편에서 수정하지 않음.
- 2026-11-14: PRD v2.0·1차 납품서 추가, 현재 자료 3개와 이전 자료로 첫 화면·README 재구성. 비밀값과 이메일은 신규 공개본에 수록하지 않음.
