# 퇴사 시뮬레이터

직장 생활의 다양한 상황에서 어떤 선택을 할지 고르는 **시나리오 기반 텍스트 게임**.

웹 브라우저에서 바로 플레이할 수 있는 단일 HTML 앱입니다.

## 등장 시나리오 (일부)

- 강제 회식
- 갑작스런 출장 지시
- 팀 해체 소문
- 갑작스러운 팀장 부재
- 야근 중 도넛 사건
- 모바일/사내 메신저 대응

각 상황마다 선택지(예: "강한 척한다" / "조용히 건넨다" / "고개를 숙인다" 등)에 따라 분기가 진행됩니다.

## 기술 스택

- 순수 HTML/CSS/JS (단일 파일)
- 외부 의존성 없음, 정적 호스팅 가능

## 실행

브라우저에서 [`index.html`](./index.html)을 직접 열거나, GitHub Pages 등으로 배포하면 됩니다.

```bash
# 로컬 실행 예시
open index.html
# 또는 간단한 정적 서버
python3 -m http.server 8000
```

## 파일

- [`index.html`](./index.html) — 앱 본체 (배포용)
- [`resignation_simulator.html`](./resignation_simulator.html) — 동일 내용 백업본
