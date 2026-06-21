# NexFlow — AI 워크플로우 자동화 SaaS 랜딩 사이트

가상의 AI 워크플로우 자동화 서비스 "NexFlow"를 소개하는 마케팅 랜딩 사이트입니다. 별도의 빌드 도구나 서버 없이 동작하는 순수 정적 웹사이트로, 프리미엄 다크 테마와 다양한 인터랙션 효과를 담고 있습니다.

## 주요 기능

- **3개 페이지 구성** — 홈(`index.html`), 기능 소개(`features.html`), 요금제(`pricing.html`)
- **파티클 네트워크 배경** — 캔버스로 그린 입자들이 서로 연결되고 마우스에 반응하는 배경 애니메이션
- **커서 글로우 효과** — 마우스를 따라다니는 빛 번짐 효과
- **스크롤 등장 애니메이션** — Intersection Observer 기반으로 요소가 화면에 들어올 때 순차적으로 나타나는 연출
- **숫자 카운트업** — 통계 수치가 0부터 목표값까지 차오르는 애니메이션
- **마그네틱 버튼 & 3D 틸트 카드** — 마우스 위치에 반응해 움직이는 버튼과 카드
- **요금제 월/연 결제 토글** — 청구 주기 전환에 따라 가격이 바뀌는 토글
- **결제 모달 · FAQ 아코디언 · 기능 탭 전환** — 요금제 및 기능 페이지의 인터랙티브 UI

## 실행 방법

빌드 과정이 필요 없는 정적 사이트입니다. 다음 중 한 가지 방법으로 실행하세요.

브라우저에서 `index.html` 파일을 직접 열어도 동작합니다. 다만 일부 기능을 위해 로컬 서버로 여는 것을 권장합니다.

```bash
cd nexflow-saas

# Python이 설치된 경우
python -m http.server 8000

# 또는 Node.js가 설치된 경우
npx serve
```

이후 브라우저에서 `http://localhost:8000` 에 접속합니다.

## 기술 스택

- HTML5 / CSS3 (글래스모피즘, mesh 그라디언트, CSS 애니메이션)
- 바닐라 JavaScript (Canvas API, Intersection Observer, requestAnimationFrame)
- Pretendard 가변 폰트 (CDN)

## 폴더 구조

```
nexflow-saas/
├─ index.html        홈 (히어로 · 핵심 가치 · 후기)
├─ features.html     기능 소개
├─ pricing.html      요금제
├─ css/styles.css    전체 스타일
├─ js/main.js        인터랙션 스크립트
└─ Design.md         디자인 시스템 정의
```
