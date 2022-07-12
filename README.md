# management
신규 출시 앱 히스토리를 적을 Repo입니다
- 가계부 관련 어플입니다 ( 주제: 준비 )

<br/><br/>
## 고려사항
- Storyboard & 필요시 Code 적용
- DarkMode

<br/><br/>
### Stack
- Swift, UIKit & SwiftUI (상황에 맞게 혼용할 계획)
- MVVM Pattern
- SwiftLint(획일화 및 클린코드), SwiftGen(개별 관리 가능), RxSwift 또는 Combine(고민 중), SwiftRealm(NOSQL 장점)
- TestFlight ( CI/CD )

<br/><br/>
### 특징
- 라이브러리 설치: Cocoapods를 사용하여 단일 관리 포인트 사용
- 라이브러리 사용: 라이브러리 사용을 최소화하며, 간편한 라이브러리를 쓰더라도 추후 제거할 예정
- 

<br/><br/>
## 회고
- 추후 작성 예정

<br/><br/>
## 기획
### 아키텍처
<img width="640" alt="스크린샷 2022-04-30 오후 8 49 12" src="https://user-images.githubusercontent.com/80211277/166104289-c909fc59-5e66-43d1-bf10-349091b7903e.png">


### 기능
- CURD (예산, 목록, 세부사항)
- 상세 Report (종합 Report)
- 백업 및 복구
- 버전

### 추가기능
- 설정 (FaceID, PIN number)
- 외부 내보내기 (초대..?)
- 다크모드
- 위젯 (워치..?)
- 달력

<br/><br/>
## 초기 UI 디자인
<img width="480" alt="스크린샷 2022-04-28 오전 12 05 52" src="https://user-images.githubusercontent.com/80211277/165551391-a123fc27-f69b-402c-baaa-65b1685eee19.png">
<img width="480" alt="스크린샷 2022-04-27 오후 12 48 22" src="https://user-images.githubusercontent.com/80211277/165436549-6c6fd653-cbe8-417f-91c0-532273cd3e80.png">
<img width="400" alt="스크린샷 2022-04-27 오후 12 48 33" src="https://user-images.githubusercontent.com/80211277/165436554-98f35331-e145-4cb0-9cbd-e982eb05a677.png">

<br/><br/>
## 이슈
[SwiftUI Architecture에 대하여](https://github.com/Lautner-kwangho/management/issues/1)
