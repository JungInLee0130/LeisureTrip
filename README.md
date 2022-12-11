# Leisure Trip

11.5 <br>
frontUsingBack 브랜치 <br>
카카오 로그인 구현<br>
.gitignore에 strings.xml -> 앱키보유해서 깃이그노어 처리<br>
@string/kakao_app_key는 kakao + 앱키를 입력해야 카카오 로그인 구동이 가능하고, 정보를 받아올수있음.<br>

브랜치 병합은 보류.

11.20 <br>
플라스크 통신 완료<br>
build.gradle okhttp 의존성 추가<br>
MainActivity 2개라 하나 삭제 (login 폴더가 진짜) <br>

12.10 <br>
최종 프로젝트 완성<br>
Android Studio + Flask + retrofit<br>
Flask : local Server (port : 5000)  + RDS 연결<br>
Flask 코드는 보안상 올리지 않음<br>
Rest API: 시간별 혼잡도, 실시간 객체 데이터<br>
kakao_app_key 비식별화<br>

시스템 관계도<br>

![캡스톤 백엔드 아키텍처](https://user-images.githubusercontent.com/70370578/206893518-7dd75908-b694-4f36-be04-da08c372bccd.png)
