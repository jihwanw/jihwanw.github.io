# TRAFFIC-STRATEGY — jihwanw.github.io

목표: 검색·소셜 유입 → insight 콘텐츠 소비 → **강연·기고·자문 문의(contact_click)** 전환

## 1. 전환 퍼널과 측정

```
유입 (검색/LinkedIn/직접) → 콘텐츠 (insight/메인) → 신뢰 (PDF 다운로드) → 전환 (contact_click)
```

GA4 이벤트 체계:
- `file_download` — PDF 다운로드 (file_name, link_location 파라미터). 관심 강도 신호
- `contact_click` — mailto 클릭 (link_location: main_kr/en, insight_cta_kr/en + page_path). **핵심 전환 지표**
- 월간 점검: 어떤 insight가 contact_click을 만드는가 → 그 주제로 후속 콘텐츠 기획

## 2. 타깃 키워드 맵

| 키워드 그룹 | 예시 | 담당 콘텐츠 | 경쟁도 |
|---|---|---|---|
| 신조어 선점 | 금융 슈퍼에이전트, Agent Native, 하네스 엔지니어링 | super-agent, harness | 낮음 — 최우선 |
| 시의성 기술 | Kimi K3 분석, TurboQuant, LLM Wiki Karpathy | kimi-k3, turboquant, llm-wiki | 낮음~중간 |
| 브랜드 | 우지환 AI, Jihwan Woo AI | 메인, About | 낮음 |
| 산업 키워드 | 에이전틱 AI 도입, AI 기술 가치평가, 뉴로심볼릭 AI | Advisory, 저서, DBR | 높음 — 장기 |

원칙: **시의성 주제를 한국어로 가장 빨리, 가장 깊게** 다루는 것이 최대 무기. 경쟁 콘텐츠가 생기기 전 게재가 곧 SEO.

## 3. 콘텐츠 운영 루틴 (게재 시 체크리스트)

1. insight 페이지 제작 (KR/EN) — TechArticle JSON-LD, hreflang, canonical 포함
2. 자체 제작 PDF 있으면 assets/docs에 추가 + GA 태깅 링크
3. 메인 KR/EN: Latest Insights 그리드 카드 + **상단 하이라이트 배너 교체**
4. /insights/ 인덱스 페이지에 항목 추가
5. feed.xml에 item 추가
6. sitemap.xml URL 추가 + lastmod 갱신
7. push 후 Search Console URL 검사 → 색인 생성 요청 (KR/EN)
8. LinkedIn 포스트 (아래 4번)

## 4. LinkedIn 연계 (주 1~2회) — PDF 포스트 중심

현행 방식: 콘텐츠를 PDF 문서 포스트로 공유 (링크 공유보다 도달률 높음 — 유지)

게재 체크리스트:
1. LinkedIn용 PDF 마지막에 **CTA 페이지** 추가 (템플릿: 로컬 기고/linkedin-cta-page.pdf)
   - jihwanw.github.io/insights + QR(UTM: utm_source=linkedin&utm_medium=pdf) + 문의 이메일
   - PDF 내 링크는 LinkedIn 뷰어에서 클릭 불가 → 타이핑 가능한 짧은 주소 + QR이 필수
2. 포스트 본문에 해당 글 URL + UTM 병기:
   https://jihwanw.github.io/insights/<slug>/?utm_source=linkedin&utm_medium=post
3. 측정: GA4에서 utm_medium=pdf(QR 유입) vs post(본문 링크) 구분 추적
4. 월 1회: 과거 인기 insight 재공유 (다른 각도의 훅)

## 5. 백링크 확보

- 기고물(주간기술동향, DBR, KOITA 등) 필자 약력에 사이트 URL 포함 요청 — 기관 도메인 백링크
- 강연 시 마지막 슬라이드에 QR + URL
- 저서 프로필에 URL

## 6. 월간 점검 체크리스트 (매월 초)

- [ ] Search Console 실적: 노출 상위 검색어 / CTR 낮은 페이지 title 개선
- [ ] Search Console 색인: 미색인 페이지 확인 → 원인 파악
- [ ] GA4: contact_click / file_download 추이, 유입 채널별 전환
- [ ] 깨진 링크 점검 (외부 링크 위주)
- [ ] WORK-LOG.md 업데이트 확인

## 7. 중기 과제

- [ ] 커스텀 도메인 연결 (예: jihwanwoo.com) — 브랜드 검색·신뢰도
- [ ] Testimonials 수집 (강연·자문 의뢰인 1~2문장)
- [ ] insight별 전용 OG 이미지 (반응 좋은 글부터)
- [ ] Speaking Kit 페이지 (강연 주제 목록, 대상·시간, 연사 소개문·사진 패키지)
- [ ] EN 콘텐츠 병행 지속 — APJ 리전 강연 기회 대응

---
최초 작성: 2026-08-22
