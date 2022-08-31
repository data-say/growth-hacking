## Acquisition: 사용자를 우리 서비스로 데려오기

- 사용자 구분 >> X
    - 자발적으로 우리 서비스를 찾아오는 고객 (Organic)
    - 마케팅 활동으로 인해 우리 서비스를 찾아온 고객 (Paid)
- 사용자 구분
    - 페이스북 광고를 보고 들어온 고객
    - 친구초대를 통해 들어온 고객
    - 제휴 마케팅을 통해 들어온 고객
    - 네이버 검색을 통해 들어온 고객
    - 어떻게 들어왔는지 알 수 없는 고객 등
    - `Organic` 과 `Unknown`을 혼동하지 말자
- 생각할 문제
    - 어떻게 하면 사용자의 **유입 채널을 정확하게 추적**하고,
    - 각 **채널별 성과를 정확히 판단**할 수 있을까?

## Acquisition 관련 기본 지표

- 유저 획득 지표
    - Signup - 가입 회원
    - CAC (Customer Acqusition Cost) - 유저 획득 비용
- 광고 집행 관련 지표
    - CPC (Cost Per Click) - 클릭 당 과금되는 광고상품
    - CPI (Cost Per Install) - 인스톨 당 과금되는 광고상품
    - CPA (Cost Per Action) - 액션 당 과금되는 광고상품
    - CPM (Cost Per Mile) - 노출 당 과금되는 광고상품
    - CPP (Cost Per Period) - 기간 보장형 광고상품
    - ROAS (Return on Ads Spending) - 광고로 인한 매출액/광고비
- `CAC < LTV`
    - 회사의 생존이 걸려있는 수식
    - 같은 비율이라면 LTV를 증가시키는 게 CAC를 감소시키는 것보다 효과적임
        - CAC 50 < LTV 100 (+50)
            - `LTV +10%` CAC 50 < LTV 110 (+60)
            - `CAC -10%` CAC 45 < LTV 100 (+55)
    - CAC
        - 유저 획득 비용
        - 하나의 요약된 숫자라고 보지 말고, 채널/캠페인/날짜에 따라 쪼개서 살펴봐야 함
            - 광고비 2천만원 / 가입자 5천명 → CAC는 4000원 (X)
            - 어느 채널에 어느 캠페인으로 어느 기간동안 얼마의 예산을 집행할 것인가

## UTM Parameter

- UTM: Urchin Tracking Module
- 어느 경로를 통해서 들어왔는지 (출처를) 확인할 수 있도록 하는 파라미터
- 어느 채널에, 어떤 내용으로 마케팅 비용을 집행하는 게 가장 효과적일지
- 링크 url +
    - utm_source: 출처
    - utm_medium: 링크 유형
    - utm_campaign: 캠페인 종류
    - utm_term: 키워드 종류
    - utm_content: 내용
- Google Analytics: Campaign URL Builder