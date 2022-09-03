## 앱은 어떻게 하나요?

- 앱스토어로 이동해서 설치하는 과정에서 url의 파라미터가 유실됨
    - 다른 방식으로 기여도 측정해야 함

## Attribution

- 유저가 앱을 설치하고 실행하고 사용하는데 어떤 채널이 기여했는가
- 모바일앱의 마케팅 성과를 판단하기 위해 활용되는 개념
- 표준화가 되어있지 않으며, 각자의 서비스에 맞는 기준으로 활용

## Web vs App

- Web: UTM Parameter
- App: Attribution
    - Appsflyer, adjust, branch, Kochava

## Attribution 개념

- Attribution 구현 방식
    - 서비스마다 구현 방식이 다름
    - Install referrer, Device ID mapping, Fingerprinting
- Attribution 윈도우 (룩백 윈도우)
    - 어느 기간동안 Attribution을 인정할 것인가
- Click-through / View-through
    - 어떤 행동을 Attribution으로 인정할 것인가
- Attribution 모델
    - 여러 건의 Attribution 터치포인트가 있는 경ㅁㅁ우 종합적인 판단을 어떻게 할 것인가

## Attribution 윈도우 (룩백 윈도우), Click-through / View-through

- Click과 View에 따라 서로 다른 attribution 윈도우를 정의할 수 있음
    - 예) click은 10일, view는 3일
- 매체별로도 각각 다른 기준을 적용할 수 있음

## Attribution 모델

- Last click: 가장 최근 클릭
- Time decay: 최근에 가중치
- Linear: 모든 터치포인트에 동일한 가중치
- Position-based: 처음과 마지막에 가중치
- First click: 처음 클릭

## Attribution 설정 예시 (Appsflyer)

- 룩백 윈도우 기간, view-through attribution 인정여부 등을 파트너사마다 독립적으로 설정 가능
- 광고 플랫폼에서도 attribution은 중요한 개념
    - 페이스북은 기본적으로 클릭 후 28일로 설정되어 있음

## ROAS가 높을수록 좋다?

- ROAS에서 Return은 원래 Profit이나 현실적으로 대부분의 광고플랫폼에서 ROAS를 계산할때 Return을 Sales로 계산함
    - 원가를 계산해보았을 때 ROAS가 완전히 달라질 수 있어 주의해야 함
- 광고비를 줄이면 ROAS가 높아짐
    - 광고비와 매출이 정비례하지 않음
    - 광고비가 적은 경우 타겟팅 알고리즘이 더 엄격해지기 때문
- 여러 매체에 광고를 집행하는 경우 ROAS가 중복 집계됨
- ‘매출’이 온전히 ‘광고’로 인한 것이라고 할 수 없음
- 정답이 없는 문제
    - 주관과 철학이 필요
    - 다양한 조건으로 세팅 변경
    - 변경 후 성과를 입체적으로 측정