# 💍 결혼 준비 예산 & 축의금 관리 앱

> PC · 모바일 어디서나 사용 가능한 싱글 파일 웹 앱

---

## 🚀 GitHub Pages 배포 방법 (5분 완성)

### 1단계 — GitHub 리포지토리 생성

1. [github.com](https://github.com) 로그인
2. 우측 상단 **`+`** → **New repository** 클릭
3. Repository name: `wedding-budget` 입력
4. **Public** 선택 (Pages 무료 사용 조건)
5. **Create repository** 클릭

---

### 2단계 — 파일 업로드

1. 리포지토리 페이지에서 **Add file → Upload files** 클릭
2. `index.html` 파일을 끌어다 놓기
3. **Commit changes** 클릭

---

### 3단계 — GitHub Pages 활성화

1. 리포지토리 상단 **Settings** 탭 클릭
2. 좌측 메뉴 **Pages** 클릭
3. **Branch**: `main` 선택 → **`/ (root)`** 선택 → **Save**
4. 1~2분 후 자동 배포 완료

---

### 4단계 — 접속 URL 확인

```
https://[GitHub유저명].github.io/wedding-budget
```

예시: `https://yjjn2005.github.io/wedding-budget`

---

## 📱 모바일 앱처럼 설치하기

| 기기 | 방법 |
|------|------|
| iPhone / iPad | Safari로 접속 → 하단 공유 버튼 → **홈 화면에 추가** |
| Android | Chrome으로 접속 → 우측 상단 메뉴(⋮) → **홈 화면에 추가** |

---

## 🔄 기기 간 데이터 동기화

현재 방식: **로컬 스토리지 저장 + JSON 내보내기/불러오기**

| 방법 | 설명 |
|------|------|
| JSON 내보내기 | 하단 저장바 "내보내기" 버튼 → `.json` 파일 저장 |
| JSON 불러오기 | 다른 기기에서 앱 접속 후 "불러오기" → 파일 선택 |
| 클라우드 자동 동기화 | Firebase 연동 시 실시간 자동 동기화 가능 (별도 설정) |

---

## 📋 주요 기능

- ✅ 7개 카테고리 예산 관리 (상견례 · 웨딩홀 · 스드메 · 예물예복 · 부대비용 · 신혼여행 · 신혼집혼수)
- ✅ 축의금 직접 입력 + 엑셀 일괄 가져오기
- ✅ 엑셀/CSV 내보내기
- ✅ 신랑/신부/공동 부담 자동 집계
- ✅ 실시간 예산 vs 실제 비용 비교
- ✅ 모바일 반응형 디자인

---

## 🛠 수정 방법

1. `index.html` 파일을 텍스트 편집기(VS Code 등)로 열기
2. 내용 수정 후 GitHub에 다시 업로드
3. 자동으로 사이트에 반영됨 (보통 1~2분 소요)
