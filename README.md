# bigdataparctice
201602515 김학윤
1. 프로젝트 주제 및 분석하고자 하는 Target Questions

앞으로 어떤 게임을 만들어야 유행하기 쉬울까?

이전에 나온 게임들의 장르, 판매량을 분석하여 최근 장르의 유행, 판매량을 비교하여 유행하는 게임 장르를 알 수 있다면 게임 제작의 방향성을 정해 어떤 장르를 만들지 예측을 통해 게임 제작에서 메리트를 얻을 수 있을 것이다.

2. 타겟 서비스, 수집할 데이터의 종류, 양

게임 판매량, 장르 등의 자료가 이미 많이 조사되어 있어 이 자료를 이용하기로 했다. Kaggle, Github 등에 있는 1995년 ~ 2021년까지의 여러 데이터를 사용한다.

1995년 ~ 2016년의 비디오 게임명, 출시연도, 장르, 판매 데이터 약 15,000개, 스팀 게임명과 플레이시간 데이터 약 100,000개, 1995년 ~ 2021년의 게임들의 메타크리틱 점수 약 12000개, 1995년 ~ 2021년의 게임명, 출시연도 약 15,000개, 게임 목록, 판매량 데이터 등 여러 cvs파일을 사용하여 분석한다.

3. 대략적인 프로젝트 진행 타임라인

여러 데이터의 날짜 형식, 게임명 등 중복되는 자료들을 제거하고 통합한다.

통합된 데이터 중에 같은 게임이지만 다르다고 분류하거나, 출시 연도 등 데이터가 정확히 일치하는지 검사한다.

게임 수 대비 판매량, 장르별 판매량, 지역별 판매량, 장르별 판매량 등 여러 조건에서 분석한다.

추가적으로 필요한 조건에 대해 생각해보고 추가 분석한다.

이 후 분석한 자료에서 순위권을 분석하여 어떤 장르를 어떤 지역에서 출시해야 유리할 지 정한다.

4. 예상되는 어려운 점 및 해결방법

게임 목록과 판매량 플레이 시간 등 데이터 셋 자체는 충분히 많다고 생각한다.

그래서 자료들 간의 중복 자료, 필요 없는 부분 등을 잘 고려하고 제거, 통합하는 것이 중요하다고 생각한다. 자료끼리 서로 중복되는 내용이지만, 고유 값이 달라 서로 다르게 인식할 때 이를 서로 통합해 주고 중복 측정하지 않도록 해야 한다.

또한 판매량이 없는 자료도 있어 판매량 비교를 할 때 이 자료를 어떻게 처리할 지 고민해야한다. 판매량을 같은 장르의 다른 게임들의 평균 값으로 처리하면 판매량이 너무 높아질 것 같아서 그냥 삭제하는 방향으로 결정할 것이다. 

하지만 자료 수가 부족해지면 판매지역, 장르 등 다른 부분을 고려해서 비슷한 다른 자료들을 참고해서 수정해야할 것 같다. 이 부분은 좀 더 생각해 봐야한다.

특정 장르에서 유독 높은 판매량을 보이는 데이터들이 있다. 같은 장르의 다른 게임들은 판매량이 낮은데 특정 게임에 의해 평균치가 높아지는 경우, 이는 인기있는 장르인가에 대해 고민해야 한다. 완성도 높은 게임 하나로 인하여 장르 전체의 평균치가 높아지는 것은 정확하지 않다고 생각하여 어느정도 가중치를 둬야 한다.

최근 동향을 살펴보기 위해서 1995년의 데이터는 필요 없을 것이라고 예상되어 2005년이나 2010년 이후의 자료를 살펴봐도 괜찮을 것 같다. 먼저 1995년도부터 데이터를 분석한 다음, 필요 없는 자료가 많이 발생한다면 범위를 줄여서 다시 분석한다.
