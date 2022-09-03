## Deep link, Deferred deep link

- 딥링크
    - 앱 안의 특정 화면(activity)으로 이동하는 링크
- 디퍼트 딥링크
    - 딥링크의 실행을 앱 설치 이후로 지연
    - 앱이 설치되지 않은 경우 스토어로 이동해서 앱 설치 → 앱 실행하면 바로 target activity로 이동
- 일반적으로 UX 측면에서 중요도가 강조됨
    - use context 유지
- 딥링크의 가치
    - 향상된 UX
    - Attribution 성과 측정 customization
        - 웹에서의 UTM parameter와 유사
- Attribution 성과 측정
    - Identified vs Unknown 중 Unknown을 줄일 수 있음
    

## Organic Acqusition

- 판단 가능한 부분
    - Free
    - By accident
- Contents Marketing
    - 많은 경우 지속 가능하지 않음
    - 한번 터졌을 때의 영향은 독보적
    - 실험, 최적화, 반복을 통해 터지는 강도를 높이는 것은 가능
        - 터지는 빈도를 높이기는 어려움

## SEO (Search Engine Optimization) / ASO (AppStore Optimization)

- 환경
    - Web: 네이버 검색 점유율 하락
        - Google은 SEO에 따라 효과 볼 수 있음
    - App: 앱을 발견하는 데 있어, 앱스토어의 영향력이 절대적
- 기본 전략
    - (공통) 검색어 및 핵심키워드 선별
        - 검색어 랭킹, 연관검색어, 경쟁사 키워드 등록
        - (앱) `SensorTower` 사이트
        - (웹) `BlackKiwi` 사이트
    - (앱) 잘 정제된 메타데이터 입력
        - 가이드 문서
        - 체크리스트
            - 앱 타이틀 및 설명
            - 아이콘과 스크린샷
                - AB 테스트 효과 큼
                - 시기에 따라 아이콘 바꿔주는 것도 좋음
            - 비디오
                - 앱 다운로드를 30% 증가시킨다는 리포트 존재
            - 경쟁사 메타데이터
            - 업데이트 내용
    - (앱) 랜딩페이지, 썸네일(아이콘) 등에 대한 A/B 테스트를 통해 최적화
        - 검색키워드에 따라 다른 랜딩페이지
    - (웹) 검색의도에 부합하는 컨텐츠/ 사이트 배치
    - (웹) 검색엔진이 크롤링하기 좋은 사이트 구조

## Attribution 관련해서 고려해야 할 이슈들

- 툴을 사용 << 툴을 효과적으로 사용
    - 나름의 주관과 철학이 필요
    - default 설정에 대한 파악 필요
    - 룩백윈도우, view-through에 대한 처리방안, attribution 모델 등을 꼼꼼히 세팅
    - 페이스북 광고관리자와 attribution 툴 대시보드 비교
- 효과 크기 판단
    - last click인 경우가 대부분
        - 심플하지만 과연 마지막 클릭이 모든 attribution을 모두 가져가는게 맞을지
- Raw data 레벨로 확인하고 분석하는 과정 필요
    - attribution 데이터 + 서비스 데이터 조합하여 인사이트 얻을 수 있음
    - Revenue를 바탕으로 ROAS를 살펴볼 때 단순히 n일동안의 결제액을 보는게 아니라 LTV를 보는게 훨씬 의미 있음
    - 주요 attribution 툴에서 raw data를 볼 수 있는 경우가 많음
- 대시보드에 나오는 숫자 이면에 맥락을 파악해야 함

## Acquisition 정리

- 소수의 좋은 채널을 잘 관리하는 게 더 중요함
- 채널 찾기 → 최적화 → Saturate → 확장
- 채널은 계속 변화함
- Organic은 Unknown의 다른 말일 수 있음
- 채널의 성과를 어떻게 판단할 지
- Attribution 툴 사용