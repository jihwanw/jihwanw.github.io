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
