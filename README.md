# 최석진 · 프로젝트 기록

한양대학교 전기생체공학부에 다니고 있습니다. 자동차 전장 SW 검증에 관심이 많고 같은 일을 두 번 손으로 하게 되면 도구로 만들어 버리는 편입니다. 만든 뒤에는 정말 나아졌는지 숫자로 확인합니다.

> 이곳엔 무엇을 왜 했고 어떻게 풀었는지 적어 둔 곳입니다.
> 인턴 때 만든 것들은 회사와 고객사 자산이라 코드는 빼고 과정과 배운 점만 남겼습니다.

## 경력

**슈어소프트테크 · E-모빌리티 검증팀 인턴** (2026.07 ~ 2026.09)
- 주 업무: 현대케피코 VPC(차량 플랫폼 제어기) HILS 검증
- AUTOSAR 기반 제어기 모델을 다루며 신호 추적 도구, TC/TS 자동화 도구 개발

## 글 목록

### 대회
| 글 | 한 줄 요약 | 키워드 |
|---|---|---|
| [OIBC 2026 태양광 발전량 예측](posts/01-oibc2026-solar-forecast.md) | 발전소 253곳 하루 전 발전량 예측, 외부 기상 격자로 가장 큰 개선 | LightGBM · 앙상블 · GFS/ECMWF · 교차검증 |
| [쿠카톤: 자율주행 시대의 충돌 직전 안전 제어](posts/07-kookathon-presafe.md) | 누운 자세 승객을 위한 Pre-Crash 제어 아이디어와 자세 인식 데모 | 인캐빈 카메라 · SDV · 기능 융합 |

### 인턴 · 도구 개발
| 글 | 한 줄 요약 | 키워드 |
|---|---|---|
| [slxdiff · TC2TS: 모델 변경 → 테스트 영향 분석 자동화](posts/02-slxdiff-tc2ts.md) | MATLAB 없이 Simulink 모델 변경점 비교, TC→TS 자동 변환 | Simulink · 테스트 자동화 · LLM |
| [OS 신호 추출기](posts/03-os-signal-extractor.md) | 몇 시간 걸리던 신호 추적을 몇 분으로 | MATLAB · Simulink API · AUTOSAR |
| [사내 업무 자동화 크롬 확장](posts/04-chrome-extension-automation.md) | Selenium exe에서 Manifest V3 확장으로 다시 만든 이야기 | Chrome Extension · DOM · 상태 기계 |
| [다운사이징된 OpenCV 커버리지 검증](posts/05-opencv-coverage.md) | ARM64 크로스컴파일 + QEMU에서 커버리지 측정, 결함 발견 | C++ · gtest · gcovr · 기능안전 |
| [AEB 로직 엣지케이스 분석](posts/06-aeb-edge-case.md) | 60km/h 정지 차량 시나리오에서 회피/충돌 경계 찾기 | Stateflow · TTC · Euro NCAP |

## 기술
- 언어: Python, MATLAB, C++, JavaScript
- 도구: Simulink/Stateflow, LightGBM/XGBoost/CatBoost, gtest/gcovr, QEMU, Git
- 도메인: 자동차 전장 SW 검증(HILS, TC/TS), 시계열 예측
- AI 코딩 도구(Claude Code)로 요구사항을 정리하고 빠르게 프로토타입을 만든 뒤 실사용 피드백으로 다듬는 방식에 익숙합니다.
