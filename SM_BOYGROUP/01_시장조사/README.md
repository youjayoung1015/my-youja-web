# 01 시장조사 — 작업표

- 핵심 질문: 지금 K-POP 시장 어디에 빈자리가 있나?
- 입력: `00_계획/브리프.md`
- 출력(다음 단계 인계): `시장조사_요약.md` — 인사이트 5개, 각각 근거 파일 링크

| # | 작업 | 스킬 | 모델 | 산출물 | 상태 |
|---|---|---|---|---|---|
| 1-1 | 조사 범위·질문 5개 설정 (시장/타깃/경쟁/팬/환경) | source-research-report (범위 단계) | Opus | `조사범위_v0.md` | ☐ |
| 1-2 | K-POP 산업·트렌드 리서치 (최근 데뷔 그룹, 컨셉 흐름, 플랫폼) | source-research-report | Sonnet | `시장동향_v0.md` | ☐ |
| 1-3 | 시장 규모 TAM·SAM·SOM (위→아래, 아래→위) | market-sizing | Sonnet → Opus 검토 | `시장규모_v0.md` | ☐ |
| 1-4 | 거시환경 (정책·환율·한류·AI 규제 등) | pestle-analysis | Sonnet | `PESTLE_v0.md` | ☐ |
| 1-5 | 산업 구조·진입 장벽 | porters-five-forces | Sonnet | `5Forces_v0.md` | ☐ |
| 1-6 | 경쟁 그룹 3건 (가장 비슷한·가장 다른·되고 싶은) | competitor-analysis | Sonnet 수집 / Opus 비교축 | `경쟁분석_v0.md` | ☐ |
| 1-6a | SM 남아이돌 계보 (세대별 패턴) | competitor-analysis, source-research-report | Sonnet 수집 / Opus 요약 | `SM_남아이돌계보/계보_요약.md` | ☐ |
| 1-7 | 팬 반응 (댓글·리뷰 수집 → 사용자가 감성 표시) | sentiment-analysis | Sonnet | `팬반응분석_v0.md` | ☐ |
| 1-8 | 팬 인터뷰 대본 → 실시 → 요약 | interview-script → summarize-interview | Sonnet | `인터뷰대본_v0.md`, `인터뷰요약_v0.md` | ☐ |
| 1-9 | 출처 목록 정리 | - | Haiku | `출처목록.md` | ☐ |
| 1-10 | 종합: 인사이트 5 + 기획 단계 질문 | - | Opus | `시장조사_요약.md` | ☐ |

## 게이트 G1
- [ ] 모든 수치에 출처 네 조각 (무엇을·몇 개·어디서·언제)
- [ ] 판매자 글 / 겪은 사람 글 구분
- [ ] 인사이트 5개 각각 근거 파일 연결
- [ ] 1-7, 1-8은 실제 수집 원문 기반 (AI가 팬 발화를 지어내지 않음)
- [ ] `retro` 1회 → `00_읽는순서.md` 갱신

## 메모
- 1-7·1-8은 사용자 실제 수집이 필요 → 병행 진행, 늦어지면 1-10에 `(확인 필요)` 표기 후 진행
- 실존 그룹은 분석 대상으로만 인용, 기획 산출물에 이름·이미지 차용 금지
