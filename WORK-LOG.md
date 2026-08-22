# Homepage 작업 로그

## 사이트 정보
- URL: https://jihwanw.github.io/
- GitHub: https://github.com/jihwanw/jihwanw.github.io
- Google Search Console: https://search.google.com/search-console

---

## 1. Publications 업데이트
- 11개 논문 추가 (Computer Vision: ICIP 2009, ICPR 2008 Oral, MVA 2005/2007 등 + AI-driven Prediction 논문들)
- SSRN 논문 추가: "Beyond Additionality: How Policy–Strategy Alignment Shapes Innovation Outcomes" (https://ssrn.com/abstract=6333129)
- Technology Strategy & Innovation 서브카테고리 신설

## 2. MBB 파트너 수준 전문성 리뷰 & 수정
- Open Graph 메타태그, meta description, twitter card, SVG favicon(JW) 추가
- GitHub 링크 수정 → https://github.com/jihwanw
- Footer → "© 2026 Jihwan Woo"
- Advisory CTA → #contact 링크, "논의가 필요하시면 연락주세요"
- 모든 이모지 제거, 텍스트 라벨로 교체 (Finance, Enterprise, Product 등)
- CJ OliveNetworks 설명 수정 → "AI 연구소장으로서 유통, 물류, 제조, 미디어/엔터 산업 전반에 AI 기반 DX를 기획하고 수행"
- CSS: engagement-icon 텍스트 스타일, pillar-evidence "— " 접두사

## 3. Latest Insights 섹션 추가
- Advisory 아래에 신설
- DBR (뉴로심볼릭 AI, 2025), KOITA (물류/유통 AI, 2024), DT Quarterly (DT와 AI 전략, 2023)
- 3열 카드 그리드, 모바일 반응형 적용
- Nav에 Insights 링크 추가

## 4. Featured & Cited In 배너
- Hero 바로 아래에 추가
- Forbes, 동아비즈니스리뷰, 대한상공회의소, KOITA, 한국데이터산업진흥원, 소프트웨어정책연구소, KAIST, IEEE

## 5. 스크롤 애니메이션
- IntersectionObserver 기반 fade-in 효과
- Hero 섹션 제외 (즉시 표시)
- 카드 요소 stagger 효과 (80ms 간격 순차 등장)

## 6. 코드 버그 수정
- `--accent` 미정의 변수 → `--ai`로 교체 (Journal & Conference Papers 구분선)
- 모바일 engagement-grid → 1열로 변경
- 모바일 featured-logos gap/font-size 축소

## 7. SEO & 검색 노출 (2026-03-08)
- **og:url** + **canonical URL** 추가 → `https://jihwanw.github.io/`
- **JSON-LD 구조화 데이터** 추가 (Person schema: 이름, 직함, 소속, 학력, 소셜 링크)
- **sitemap.xml** 생성 → 루트 디렉토리
- **robots.txt** 생성 → 루트 디렉토리
- **Google Search Console** 등록 완료 (HTML 파일 인증)
- **Sitemap 제출** 완료 → 상태 "가져올 수 없음" (정상, 몇 시간~하루 후 "성공"으로 변경 예상)
- Contact 섹션 CTA 강화 (기고/강연 특화 문구)

---

## 확인 필요 사항 (며칠 후)

### Google Search Console 확인
1. https://search.google.com/search-console 접속
2. 좌측 "Sitemaps" → sitemap.xml 상태가 "성공"으로 변경되었는지 확인
3. 좌측 "실적" → 어떤 검색어로 노출/클릭되는지 확인 (데이터 수집까지 1~2주 소요)
4. 좌측 "페이지" → 색인 생성 상태 확인

### 검색 테스트
- Google에서 `site:jihwanw.github.io` 검색 → 페이지가 색인되었는지 확인
- "Jihwan Woo AI", "우지환 AI 전략" 등으로 검색 → 노출 여부 확인

### 파일 목록 (서버에 있어야 하는 파일)
- `index.html`
- `assets/css/style.css`
- `sitemap.xml`
- `robots.txt`
- Google 인증 파일 (`google*.html`) — 삭제하지 말 것

---

## 향후 개선 가능 사항
- 클라이언트/협업자 추천사(Testimonials) 수집 및 추가
- 블로그 서브페이지 (/insights/각 기고별 독립 URL) → 검색 유입 증가
- LinkedIn 주 1~2회 인사이트 포스트 → 홈페이지 유입 경로
- Calendly 등 자문 예약 시스템 연동
- 커스텀 도메인 연결 (예: jihwanwoo.com)

---

## 8. CES 2026 현장 리포트 페이지 (2026-03-10)

### 페이지 생성 및 구조
- `ces2026/index.html` 생성 — 다크 테마, 메인 사이트 CSS 공유
- 구조: Hero → Overview → Four Key Themes → Photo Gallery → 50 Companies → Zoox 탑승기 → Expert Analysis → Author Card → CTA → Footer
- 메인 사이트(`index.html`, `en/index.html`) Latest Insights에 CES 2026 카드 추가

### 50개 기업 섹션
- 10개 테마 그룹 (Key 5 + Sub-Key 5)으로 50개 기업 카드 구성
- 각 카드: 기업명, 설명, CES 2026 현장 인사이트, AI 전문가 시각 포함
- Expert Insight Bar 4개를 테마 그룹 사이에 배치

### Zoox 탑승기
- 직접 촬영 영상 2개 + 사진 7장 임베드
- 탑승 체험 상세 서술 + 3개 인사이트 카드 (Perception→Reasoning, 도시 인프라 공진화, 비즈니스 모델 재편)

### 톤 & 문체 수정 (3차 리비전)
- 50개 기업 카드 전체를 AI 전문가 특파원 톤으로 전면 수정
- 기존 반복 패턴 ("CES 2026: [사실]. 왜 중요한가: [인사이트]") 제거
- 카드마다 다른 문체·구조 적용 (현장 체험, 엔지니어 대화, 데모 체험, 개인 반응 등)
- 인사이트 라벨 다양화: "AI 전문가 시각:", "기술 관점:", "비즈니스 관점:", "현장 체감:", "AI 연구자 시각:" 등
- Expert Insight Bar 라벨도 특파원 노트 스타일로 변경 ("현장에서 느낀 것", "쇼 플로어에서 읽은 패턴" 등)
- Overview, Theme Cards, Gallery, Zoox, Expert Analysis는 이전 리비전에서 1인칭 현장감 톤으로 수정 완료

### CES 폴더 위치 검토
- `ces2026/`를 `assets/` 하위로 이동하지 않고 루트 레벨 유지 결정
- 이유: 독립 콘텐츠 페이지 (URL: `jihwanw.github.io/ces2026/`), `en/`과 동일한 콘텐츠 디렉토리 구조

### 불필요 사진 정리
- `ces2026/` 폴더에서 18장 삭제, 12장 + 영상 2개 유지

### Zoox/Waymo 사진 분리 (2026-03-10)
- 기존 Zoox 섹션에서 Waymo 사진(017~029)을 분리하여 별도 Waymo 섹션 신설
- Zoox 섹션: 실제 Zoox 사진 6장(001, 002, 005, 007, 009, 010) + 영상 2개 + 탑승 인사이트 3개
- Waymo 섹션: Waymo 사진 7장(017~029) + "Zoox vs Waymo: 두 가지 자율주행 전략의 대비" 분석 박스
- 상단 갤러리에서 Zoox/Waymo 사진 제거 (각 전용 섹션으로 이동)
- 네비게이션에 Waymo 링크 추가

### 네비게이션 UX 개선 (2026-03-10)
- 네비 항목 7개 → 5개로 정리: Home, Key Themes, 50 Companies, 로보택시 체험, Expert View
- Gallery 네비 항목 제거 (스크롤로 자연스럽게 노출)
- Zoox + Waymo를 하나의 `<section id="robotaxi">` 로 통합
  - 상단에 로보택시 체험 인트로 추가
  - Zoox 서브섹션 (h3) + Waymo 서브섹션 (h3) + "Zoox vs Waymo 전략 대비" 분석 박스

### Waymo/Vegas Loop 사진 정리 (2026-03-10)
- Waymo 사진 7장 → 2장(017, 018)으로 축소
- Vegas Loop 사진(021) 확인 — 이미 Vegas Loop 섹션에 배치됨
- 불필요 사진 참조(023, 026, 027, 029) 제거 완료
- Vegas Loop 섹션: The Boring Company의 지하 터널 루프 체험 + AI 통합 모빌리티 인사이트

### 50개 기업 인포그래픽 + 아코디언 (2026-03-10)
- 버블 맵: 50개 기업을 테마별 색상 버블로 한눈에 조망 (Key=보라, Sub=초록)
- 아코디언: 10개 테마 그룹의 상세 카드가 기본 접힌 상태, 클릭으로 펼침
- 버블 클릭 → 해당 테마로 스크롤 + 자동 펼침
- "전체 상세 보기/접기" 토글 버튼
- 각 theme-group에 id 추가 (theme-ad, theme-sdv 등)

### 메인 페이지 CES 2026 노출 강화 (2026-03-10)
- Hero 바로 아래에 CES 2026 하이라이트 배너 추가 (index.html, en/index.html)
- 그라데이션 배경, 호버 효과, 원클릭으로 CES 리포트 진입

### 겸손한 톤 수정 (2026-03-10)
- "AI 전문가의 시선" → "현장 리포트" / "현장에서 정리한 생각"
- "AI 전문가가 선정한" → "CES 2026에서 주목한"
- Overview에서 AWS SA/18년 자기소개 제거
- 본문 내 "AI 전문가" 표현 4곳 모두 겸손하게 교체
- Author 카드 과시적 문구 제거

### 보고서 내용 전면 보강 (2026-03-10)
- Physical AI Deep Dive 섹션 신설 (Gallery 다음, Companies 전)
  - NVIDIA Brain/Body/World 3층위 비주얼 카드
  - Cosmos Reason 2, Predict 2.5, Sim-to-Real, Vera Rubin, Alpamayo 상세
  - 로봇 혁명: Atlas/SDF, Unitree G1 $13,500, Sanctuary AI, LG CLOiD
- SDV Deep Dive 섹션 신설
  - 시장 데이터 스탯 박스 ($2,135억→$1조2,400억, SDV 비중 3.4%→90%)
  - SDV 5계층 아키텍처 비주얼 스택 다이어그램
  - OEM 전략 카드: Kia PBV/PV5/PV7, BMW iX3/Alexa, Afeela $89,900, VW IDA/ChatGPT, Geely GEEA 3.0
  - 플랫폼 전쟁: Qualcomm Snapdragon Digital Chassis, QNX Everywhere, Elektrobit+Gemini+Unreal
- Expert Analysis → "현장에서 정리한 생각" + 5대 메시지 번호 카드로 재구성
  - 구현 지능 스택, 플랫폼 통합, OS 전쟁, 인간 중심 UX, 문명 인프라
- 네비게이션 7개로 확장: Home, Key Themes, Physical AI, SDV, 50 Companies, 로보택시, 생각 정리
- 보고서 대비 커버리지: 43개 핵심 항목 중 43개 반영 (100%)

### 현장 스케치 갤러리 전면 교체 (2026-03-10)
- ces2026 폴더 내 전체 19장 사진을 갤러리에 배치
- 014(전시장 전경)를 첫 번째 와이드 사진으로 배치
- 5열 컴팩트 그리드, 클릭 시 라이트박스로 확대
- 모바일 3열 반응형

### 섹션 제목 수정
- "CES 2026에서 주목한 기업 50" → "모빌리티 분야에서 주목한 기업 50"
- 네비: "50 Companies" → "주목 기업 50"

### 50개 기업 블랭크 이슈 해결
- IntersectionObserver threshold 0.1 → 0 변경 (긴 섹션이 fade-in 트리거 안 되는 문제)

### MBB 파트너 레벨 검토 및 수정 (2026-03-10)
- 50개 기업 카드: "CES 2026:" / "왜 중요한가:" 공식 패턴 전부 제거, 5가지 자연스러운 커넥터로 분산
- Expert Insight 라벨 6개 → "현장에서 느낀 것" / "50개 기업을 돌아보며"로 통일
- Vegas Loop 제목에서 "하이퍼루프" 제거 → "지하 터널 루프를 타보다"
- 5대 메시지 뒤에 "비즈니스 임플리케이션" 섹션 추가 (5개 액션 아이템)
  - Physical AI 투자 가속화, SDV 전환 대비, 플랫폼 포지셔닝, 인간 중심 설계, 생태계 전략


---

## 9. 신간 추가: AI 시대 기술 전략 (2026-08-21)
- 교보문고 페이지 파싱 → 제목/저자/출판사/발행일/소개/표지 확보
  - AI 시대 기술 전략 · 우지환 · 커뮤니케이션북스(AI 문고) · 2026-05-04 · ISBN 9791143025654
- 표지 이미지 추가: assets/images/publications/books/ai-era-tech-strategy.jpg (교보 400px)
- KR/EN Books 섹션에 항목 추가 (소개=컴북스, 교보문고 링크)
- 카운트 갱신: stat-card 9→10, Books (9)→(10), 리서치 역량 문구 7권→10권 (KR/EN)
- sitemap.xml lastmod 갱신 (/, /en/ → 2026-08-21)

## 10. In the Press 추가: IT조선 월간AX 세미나 기사 (2026-08-21)
- 기사: 우지환 AWS "에이전틱 AI, 시작부터 명확해야 성공한다" [월간AX 6월호] (IT조선, 2026-06-30, 권용만 기자)
- 내용: 월간AX 6월 세미나에서 엔터프라이즈 AI 에이전트 트렌드와 글로벌 적용 사례 발표
- KR/EN In the Press 목록 최상단(최신순)에 추가

## 11. Insights 신규 게재: Kimi K3 + LLM Wiki (2026-08-21)
- 주간기술동향 폴더 미소개 원고 2건을 insight 페이지로 제작 (KR/EN 4개 페이지)
- insights/kimi-k3/ — Kimi K3 오픈웨이트 모델 분석 (주간기술동향 2026-08 기고 기반, 그림 3장 포함)
  - 중복 방지: TurboQuant(KV 캐시)와 겹치지 않게 오픈웨이트 경제학·산업 구조 중심 구성
- insights/llm-wiki/ — LLM Wiki 지식 관리 패러다임 해설 (Karpathy 제안, 테크 브리프 기반)
  - 중복 방지: Harness Engineering(실행 안정성)과 구분해 지식 축적·RAG 대비 중심 구성
- 메인 KR/EN Latest Insights 그리드 최상단에 카드 2개씩 추가
- sitemap.xml에 4개 URL 추가

## 12. Insight PDF 리포트 첨부 (2026-08-21)
- 자체 제작 PDF 2건을 assets/docs에 추가: kimi-k3-report.pdf (k3.pdf 최신본), llm-wiki-report.pdf
- insight 페이지 4개(KR/EN)에 "보고서 전문 보기 (PDF)" 버튼 추가 (하네스 페이지와 동일 패턴)
- 메인 KR/EN insight 카드에 PDF 링크 병기 (DBR 카드 패턴)
- GA4 향상된 측정의 file_download 이벤트로 다운로드 추적 가능
- GA4 이벤트 태깅 추가: 모든 PDF 링크 18개에 file_download 이벤트 (file_name, link_location 파라미터)
- EC2 SSH 장애 대응: 사내 SSH egress IP 로테이션으로 접속 불가 → SG에 15.248.4.0/23 (corp NAT 대역) 추가로 해결

## 13. Insights 신규 게재: 금융 슈퍼에이전트 덱 (2026-08-21)
- 사용자 제작 HTML 슬라이드 덱(39장)을 insights/super-agent/로 호스팅 (덱 디자인 원본 유지)
- 덱 head에 GA 태그, meta description/OG, canonical, favicon 추가 + 좌상단 홈 복귀 링크
- PDF 버전을 assets/docs/financial-super-agent-deck.pdf로 추가
- KR/EN 메인 Latest Insights 최상단에 카드 추가 (PDF 링크 GA 태깅 포함, EN 카드는 한국어 덱 안내)
- sitemap.xml에 URL 추가

## 14. 온사이트 SEO 개선 (2026-08-22)
- insight 페이지 10개(5쌍 KR/EN)에 TechArticle JSON-LD 추가 (headline/description은 각 페이지 메타 재사용, datePublished 지정)
- 동일 페이지들에 hreflang(ko/en/x-default) 상호 링크 추가
- 슈퍼에이전트 덱 SEO 보완: 덱을 deck.html로 이동, index.html에 검색용 요약 아티클 신설 (JSON-LD 포함)
  - /insights/super-agent/ URL 유지 → 색인 요청 유효, 크롤러가 읽을 수 있는 본문 확보
- 내부 링크: insight 페이지 10개에 "관련 글" 섹션 추가 (kimi-k3↔turboquant, llm-wiki↔harness 등)
- 메인 카드: 슈퍼에이전트 "분석 읽기"(아티클) + "덱 보기"(deck.html)로 분리

## 15. Hero 하단 Latest 배너 갱신 (2026-08-22)
- 3~4월 콘텐츠(Physical AI, 하네스, TurboQuant) 배너 3개를 최신 게재물로 교체 (KR/EN)
  - 금융 슈퍼에이전트 / Kimi K3 / LLM Wiki (라벨 "New ·")
- CES 2026 배너는 유지, 기존 글은 Latest Insights 그리드에서 계속 접근 가능
- 운영 원칙: 신규 insight 게재 시 상단 배너도 함께 갱신할 것

## 16. 사이트 전면 개선: 전환·성능·허브·브랜드·전략 (2026-08-22)
- 전환: insight 페이지 11개에 강연·기고·자문 CTA 블록 추가 (contact_click GA 이벤트), 메인 mailto 태깅
- 성능: 책 표지 9장 + 프로필 사진 WebP 변환 (931KB+342KB -> 147KB, 약 88% 절감), img src 교체
- 허브: /insights/ 인덱스 페이지 신설 (7개 콘텐츠 목록), feed.xml RSS 피드 생성, 메인 head에 RSS 링크
- Talks: 월간AX 6월 세미나 발표(엔터프라이즈 AI 에이전트) KR/EN 최상단 추가
- 브랜드: og-default.png (1200x630) 생성, 16개 페이지 og:image 교체
- 전략: TRAFFIC-STRATEGY.md 수립 (퍼널·키워드 맵·게재 체크리스트·LinkedIn 루틴·월간 점검)
