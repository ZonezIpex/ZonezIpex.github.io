<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Noto+Sans+KR&size=34&pause=1200&color=111111&center=true&vCenter=true&width=1000&lines=ZonezIpex.github.io;Personal+Web+Portfolio" alt="Portfolio Typing" />
</p>

---

# Web Portfolio (GitHub Pages)
이 레포는 **개인 웹 포트폴리오(정적 사이트)**이며, GitHub Pages로 배포됩니다.  
`index.html` **단일 파일**로 동작하고, 프로젝트 썸네일/로고·포스터 이미지/이력서·자기소개서·포트폴리오 PDF 같은 정적 파일을 함께 관리합니다.

> URL: `https://zonezipex.github.io` (GitHub Pages 설정 기준)

<br/>

## ✅ 페이지 구성(섹션)
페이지는 아래 섹션으로 구성되어 있습니다.

- Intro (`#intro`)
- Growth (`#growth`)
- Skills (`#skills`)
- Career (`#career`)
- Logos & Posters (`#posters`)
- Projects (`#projects`)
- Contact (`#contact`)

상단에서는 아래 기능을 제공합니다.
- 🌙 다크모드 토글 (`darkToggle`)
- 🌐 한국어/영어 전환 (`langToggle`)
- ☰ 모바일 메뉴 토글 (`menuToggle`)
- 🔎 로고/포스터 검색 + 탭 필터(로고/포스터) (`#posters`)
- 🔎 프로젝트 검색 + 태그 필터(Projects 섹션) (`#projects`)

<br/>

## 🖼️ Logos & Posters 섹션 (로고/포스터)
`index.html` 내부의 `POSTERS` 배열로 카드가 렌더링됩니다.

- 로고/포스터 탭 전환(로고/포스터)
- 검색(제목 기반)
- 캐러셀(좌우 이동)

이미지 파일은 주로 `제작한이미지/` 폴더에서 관리합니다.  
(한글 경로를 쓸 때는 퍼센트 인코딩 경로 사용을 권장합니다.)

<br/>

## 📌 Projects 섹션에 올라가는 프로젝트 (최신순)
현재 `index.html` 내부의 `PROJECTS` 배열로 프로젝트 카드가 렌더링됩니다.

- **IT자산장부 — 사내 IT 자산 대여·반납·검수·통합관리 DB 설계**  
  기간: **2026.01.05 ~ 2026.01.21**  
  자산 등록 → 할당/출고 → 반납요청 → 회수 → 검수(수리 여부 판정) → 가용 복귀/수리 처리 흐름을 DB 모델로 정리한 프로젝트  
  - GitHub: https://github.com/ZonezIpex/IT-Asset-Register  
  - Thumbnail: `IT자산장부.png`

- **면접몬 — AI 모의면접 & 피드백 플랫폼**  
  기간: **2025.08.28 ~ 2025.12.04**  
  직무/기업 맞춤 질문과 STAR 구조 피드백으로 실전 감각을 키우는 서비스  
  - GitHub: https://github.com/ZonezIpex/MenjupmonIntroduction.git  
  - Thumbnail: `면접몬 메인페이지.png`

- **대팡 — 필기·요약·퀴즈 통합 AI 학습 플랫폼**  
  기간: **2025.08.27 ~ 2025.12.03**  
  학습 자료를 한 곳에 모으고, AI로 퀴즈를 생성해 복습 효율을 높이는 서비스  
  - GitHub: https://github.com/ZonezIpex/DaepangIntroduction.git  
  - Thumbnail: `대팡 메인페이지.png`

- **AiR — 회사 맞춤 AI 이력서 플랫폼**  
  기간: **2025.04.19 ~ 2025.06.22**  
  공고/양식을 기반으로 맞춤 이력서 제작을 돕는 서비스  
  - GitHub: https://github.com/ZonezIpex/Team_project.git  
  - Thumbnail: `이력서 플랫폼 메인페이지.png`

- **코드어드벤쳐 — 게임형 코딩 학습 플랫폼**  
  기간: **2024.04 ~ 2024.07**  
  스테이지를 클리어하며 언어를 익히는 게임 기반 학습 프로젝트  
  - GitHub: https://github.com/ZonezIpex/Codeadventuredealim.git  
  - Thumbnail: `코드어드벤쳐 메인페이지.png`

<br/>

## 📁 파일 구성
<pre>
ZonezIpex.github.io
├─ index.html
├─ README.md
├─ 증명사진.png
├─ 이력서.pdf
├─ 자기소개서.pdf
├─ 포트폴리오.pdf
├─ IT자산장부.png
├─ 대팡 메인페이지.png
├─ 면접몬 메인페이지.png
├─ 이력서 플랫폼 메인페이지.png
├─ 코드어드벤쳐 메인페이지.png
└─ 제작한이미지/
   ├─ AIR로고.png
   ├─ AIR포스터.png
   ├─ IT자산장부로고.png
   ├─ IT자산장부포스터.png
   ├─ 대팡로고.png
   ├─ 대팡포스터.png
   ├─ 면접몬로고.png
   ├─ 면접몬포스터파일.png
   ├─ 코드어드벤처로고.png
   ├─ 코드어드벤처포스터.png
   ├─ 입영통지서.png
   └─ 헬다.png
</pre>

<br/>

## ✏️ 수정 포인트(자주 건드리는 곳)
- **로고/포스터 카드 수정**: `index.html` 안의 `const POSTERS = [...]`
  - title/image/type(poster|logo) 변경
- **프로젝트 카드 수정**: `index.html` 안의 `const PROJECTS = [...]`
  - title/subtitle/highlights/image/links/tags/tech 변경
- **소개/문구/다국어 텍스트 수정**: `index.html` 안의 `const I18N = {...}`
- **스킬 태그 수정**: `index.html` 안의 `const SKILLS = {...}`
- **이력서/자기소개서/포트폴리오 교체**
  - `이력서.pdf`, `자기소개서.pdf`, `포트폴리오.pdf` 파일을 같은 이름으로 교체하면 링크 유지됨
- **썸네일 교체**
  - 이미지 파일명을 유지한 채 교체하면 경로 수정 없이 반영됨

<br/>

## ▶️ 로컬에서 확인
정적 HTML이라 빌드 없이 바로 확인 가능합니다.

### 1) 가장 간단한 방법
- `index.html` 더블클릭으로 브라우저에서 열기

### 2) (추천) Live Server
VSCode 확장 **Live Server**로 열면 리소스/경로 확인이 더 편합니다.

<br/>

## 🚀 GitHub Pages 배포
이 레포가 `username.github.io` 형태의 레포라면, 아래 중 하나로 배포됩니다.

- **Settings → Pages → Branch 선택(main / root)**  
- 커스텀 도메인이 있다면 Pages 설정에서 연결

> 커밋/푸시 후 Pages 빌드가 끝나면 URL에 반영됩니다.
