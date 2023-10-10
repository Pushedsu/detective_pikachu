# detective_pikachu
포켓몬 빵을 찾아라!

호서대 컴퓨터공학과 UI/UX프로그래밍 강의 팀 프로젝트입니다.

참여인원: 김민수, 정태현, 오윤지, 저우환위

프로젝트 진행 기간은 2022.5월 중순 ~ 7월 초 입니다.

## 프로그램 개요 및 설명
앱을 실행해 현재 자신의 위치와 가장 가까운 가게의 포켓몬 빵 재고를 알아 보세요.
## 전체 구조도
![image](https://github.com/Pushedsu/PetCareService-client/assets/109027302/c14331a3-782f-4002-8ec0-82caaabc1021)

## 전체 구조도 설명

## 실행 화면

### 1. Splash screen
   - 앱의 처음 시작 화면
   - 색상 #FEEB70
     
     <img src="images/splash1.png" width="450px" height="300px" title="px(픽셀) 크기 설정" alt="RubberDuck"></img><br/>

### 2. Location screen
   - 사용자 위치 정보가 꺼져있을 때
   - 사용자 위치 정보가 켜져있을 때
   - 찜한 스토어 개수 만큼 하트 위 숫자 증가

| ![image](https://github.com/Pushedsu/object_crowding_alarm_program/assets/109027302/dd96fcf2-edc5-49f0-bccd-8b417dbb4d87) | ![image](https://github.com/Pushedsu/object_crowding_alarm_program/assets/109027302/39a72cee-e159-44f0-ac0c-4d46c2cfef85) |
|:-------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------:|
|     `'사용자 위치 정보가 꺼져있을 때'`  |     `'사용자 위치 정보가 켜져있을 때'`  |

### 3. product info screen
   - 캐릭터 검색 기능
   - 정렬 기능
   - 좋아요 한 캐릭터만 골라 보기 기능 

![image](https://github.com/Pushedsu/PetCareService-client/assets/109027302/97562505-08f4-4b64-b179-9dc991c338d3)

### 4. favorite screen
   - 찜한 스토어가 없을 때 찜하러 가기 누르면 첫 번째 탭(Location screen)으로 이동
   - 찜한 스토어가 있을 때 찜한 스토어 개수가 뜨고 찜한 가게 정보가 리스트보이는 기능

| ![image](https://github.com/Pushedsu/PetCareService-client/assets/109027302/bf63be39-86df-4016-a2bf-689de7750dfc) | ![image](https://github.com/Pushedsu/PetCareService-client/assets/109027302/39a75922-d9a8-4927-9c9f-f93aa2c21c08) |
|:-------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------:|
|     `'찜한 스토어가 없을 때'`  |     `'찜한 스토어가 있을 때'`  |

### 5. fourth screen
   - 더보기 화면
![image](https://github.com/Pushedsu/PetCareService-client/assets/109027302/f119613e-a568-485a-b58a-d01fd43271aa)

## 주요 기능 설명
1. 주변 상점 정보 불러 오기 기능
   - 사용자 기기 위치 값을 얻어 주변 상점 정보를 불러 옵니다.
   - 사용자에게 리스트 형식으로 불러온 정보를 제공 합니다.

2. 마커 기능 및 재고 
   - 지도 위에 마커 표시를 해 상점 위치 정보를 시각적으로 제공합니다.
   - 마커를 클릭하면 재고 정보를 표시합니다.

3. 실시간 위치 표시 기능
   - 지도 위 지신의 위치와 가장 가까운 가게를 찾아보세요.
   
4. 상점 찜하기 기능
   - 상점 찜하기 기능을 제공합니다.
   
5. 캐릭터 찜하기 기능
   - 캐릭터 찜하기 기능을 제공합니다.

6. 더보기 화면
   - 사용자의 정보를 표시합니다.


