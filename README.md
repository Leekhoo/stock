현대자동차 주식을 매수한 기념으로 코드를 만들어봤습니다.

우선 현대자동차 기업 정보를 데이터 크롤링으로 수집을 해서 현대 자동차의 주식 가격을 예측을 한 뒤, 주식이 오를 것이라고 판단이 되면 메일로 보내주는 코드를 구현하려고 했습니다.

하지만 주식 가격은 기업 정보만으로 예측하기 불가능하다는 것을 깨달았습니다. 그래서 추후 기업 정보, 시장 동향 파악을 하는 방법을 공부해서 업데이트 할 예정입니다.

![기업정보](https://github.com/Leekhoo/stock/assets/137920352/71dbd0f5-4e44-4055-ad81-ffe8bc5e3770)

위의 문제점을 깨닫고, 단순히 현대자동차 주식 가격을 알려주는 알림 서비스 코드를 구현해봤습니다.
우선 주식 장이 열리는 9시, 주식이 마감하는 15시에 현대자동차 주식 가격을 알려주는 함수를 작성했습니다.
그리고 현대자동차 주식 가격을 계속 지켜보다가 20만원 이상 주식이 오르면 메일로 알려주는 함수도 추가했습니다.

아직은 현대 자동차 주식이 20만원을 넘지 않아서 메일이 오지 않고 있습니다.

![주식](https://github.com/Leekhoo/stock/assets/137920352/a01e3634-3ec5-473a-b3a2-8de4495d9ae5)
