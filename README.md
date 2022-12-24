# Leisure Trip
## 2022-2 캡스톤 프로젝트
- 관광지 CCTV 데이터를 사용하여 관광지 혼잡도를 나타내주는 어플리케이션<br><br>

# 주요기능
- 실시간 혼잡도, 시간별 혼잡도(9 to 18), 차량 및 보행자 실시간 비율<br><br>


# 진행상황<br>
## 11.5.Sat <br>
frontUsingBack 브랜치 <br>
- 카카오 로그인 구현 : Using KaKao Login Api
- .gitignore에 strings.xml -> 앱키보유해서 깃이그노어 처리<br>
- @string/kakao_app_key는 kakao + 앱키를 입력해야 카카오 로그인 구동이 가능하고, 정보를 받아올수있음.<br>

- 브랜치 병합은 보류.

## 11.20.Sun <br>
- 플라스크 통신 완료<br>
- build.gradle okhttp 의존성 추가<br>
- MainActivity 2개라 하나 삭제 (login 폴더가 진짜) <br>

## 12.10.Sat <br>
최종 프로젝트 완성<br>
- Android Studio + Flask + retrofit<br>
- Flask : local Server (port : 5000)  + RDS 연결<br>
- Flask 코드는 보안상 올리지 않음<br>
- Rest API: 시간별 혼잡도, 실시간 객체 데이터<br>
- kakao_app_key 비식별화<br>

# 시스템 관계도<br>

![캡스톤 백엔드 아키텍처](https://user-images.githubusercontent.com/70370578/206893518-7dd75908-b694-4f36-be04-da08c372bccd.png)

# 실행 모습

## 시연 메인
![시연 메인](https://user-images.githubusercontent.com/70370578/207311514-ec056e24-ac6e-4c0e-a2c3-a89bfc4eb2a7.jpg)<br>

## 시연 로그인
![시연 로그인](https://user-images.githubusercontent.com/70370578/207320875-f863d56c-7102-44ae-b672-a73a97db7c39.jpg)<br>

## 기능
![시연1](https://user-images.githubusercontent.com/70370578/207311153-989ec619-cdd9-476e-a5e8-d532c8c7b071.jpg)<br>
![시연2](https://user-images.githubusercontent.com/70370578/207311145-a018d159-39b7-4351-8d69-ea45ba0d3723.jpg)<br>



