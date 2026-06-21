# NexFlow — 디자인 시스템

## 컨셉
**NexFlow(넥스플로우)** — AI 기반 팀 워크플로우 자동화 SaaS  
"한 번의 클릭으로 팀 전체가 달라진다"는 메시지를 시각·모션으로 전달.

## 톤 & 무드
- **프리미엄 다크**: 깊은 네이비/블랙 베이스 + 전기 보라·시안 액센트
- **미래지향적**: 글래스모피즘, 글로우, 파티클 네트워크
- **신뢰감**: 깔끔한 타이포, 명확한 CTA, 숫자 기반 소셜 프루프

## 컬러 팔레트
| 역할 | 값 |
|------|-----|
| 배경 | `#050510` → `#0a0a1a` |
| 액센트 1 | `#7c3aed` (보라) |
| 액센트 2 | `#06b6d4` (시안) |
| 액센트 3 | `#f472b6` (핑크) |
| 텍스트 | `#f8fafc` / `#94a3b8` |
| 글래스 | `rgba(255,255,255,0.05)` + blur |

## 타이포그래피
- **Display**: Pretendard (한글 최적화)
- **Hero**:  clamp(2.5rem, 6vw, 5rem), weight 800, letter-spacing -0.03em
- **Body**: 1rem / 1.125rem, line-height 1.7

## 모션 원칙
1. **입장**: staggered fade-up (0.1s 간격)
2. **호버**: scale 1.02 + glow intensify
3. **스크롤**: Intersection Observer 기반 reveal
4. **배경**: canvas 파티클 + CSS mesh gradient (60fps 목표)
5. **CTA**: magnetic button + ripple

## 페이지 구조
- `index.html` — 히어로, 핵심 가치, 데모 프리뷰, 소셜 프루프
- `features.html` — 6대 기능, 인터랙티브 탭 데모
- `pricing.html` — 3티어, 월/연 토글, FAQ

## 인터랙션 하이라이트
- 커서 따라다니는 글로우 오브
- 3D tilt 카드 (마우스 위치 기반)
- 숫자 카운트업 애니메이션
- 가격 페이지 billing 토글 + 카드 flip
- 기능 페이지 라이브 프리뷰 패널
