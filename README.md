## 프로젝트명:
현대자동차 주식 알림 서비스 코드

## 프로젝트 소개:
이 프로젝트는 현대자동차의 주식 가격을 모니터링하고, 특정 조건이 충족될 때 알림을 보내는 서비스를 구현한 것입니다. 아래는 코드의 구조와 주요 기능을 설명한 내용입니다.

## code 구조:
- main.py : 프로그램의 시작점이며, 주식 가격 모니터링과 알림 발송을 관리합니다.
- stock_monitoring.py : 주식 가격 정보를 크롤링하고 가격 변동을 모니터링하는 기능을 포함합니다.
- email_service.py : 이메일 발송 기능을 제공합니다.

## code 주요기능:
- 주식 가격 모니터링: stock_monitoring.py 모듈은 네이버 주식에서 현대자동차의 주식 가격을 크롤링하여 주기적으로 확인합니다.
- 가격 변동 감지: 현재 주식 가격을 이전에 저장된 가격과 비교하여 변동을 감지합니다. 변동이 감지되면 알림을 발송합니다.
- 이메일 알림: email_service.py 모듈은 Gmail 서비스를 이용하여 이메일을 발송하는 기능을 제공합니다. 가격 변동이 감지되면 설정된 이메일 주소로 알림을 발송합니다.
- 사용자 설정: 사용자는 프로그램의 설정을 main.py에서 변경할 수 있습니다. 주기적인 크롤링 간격, 알림을 받을 가격 등을 설정할 수 있습니다.

## code 사용방법:
1. main.py를 실행합니다.
2. 프로그램은 설정된 주기마다 네이버 주식에서 현대자동차 주식 가격을 크롤링하여 변동을 모니터링합니다.
3. 가격 변동이 감지되면 설정된 이메일 주소로 알림을 발송합니다.

## 출력 결과 예시:
1. 아래 사진은 기업 재무재표를 데이터 크롤링으로 수집을 한 뒤, 엑셀 파일로 정리한 것입니다.

![기업정보](https://github.com/Leekhoo/stock/assets/137920352/71dbd0f5-4e44-4055-ad81-ffe8bc5e3770)

2. 아래 사진은 메일로 주식 가격을 알려준 사진입니다.

![주식](https://github.com/Leekhoo/stock/assets/137920352/a01e3634-3ec5-473a-b3a2-8de4495d9ae5)
