# **미아 방지 프로젝트**
<img src="https://github.com/user-attachments/assets/cffbe5fc-a92b-4007-ac42-f88cd5554aad" alt ="무인파손시스템" width = "600" height="400">

## 프로젝트 소개
- 해마다 실종 아동 신고수가 2만건 이상이 발생하고 1년이 넘도록 찾지 못하는 사례가 **871건**으로 적지 않는 추세를 보이고 있음
-  ***NFC기능을 부착한 팔찌*** 부착하여 앱을 통해서 아동의 정보를 출력하여 실종 아동을 방지하기 위해서 구현된 프로젝트

</br>

## 팀원 구성 & 역할
<div align="center">


| **김수겸** | **채수명** | **이지은** | **조형석** |
| :------: |  :------: | :------: | :------: |
| <img src="https://github.com/user-attachments/assets/e553fca2-ffae-421f-8e77-bed2e1a7bf32" height=150 width=150> <br/>  **Web개발** | <img src="https://github.com/user-attachments/assets/c1d237ad-1685-44a5-b476-b0da86dcdaef" height=150 width=150> <br/> **DB및PHP설계** |<img src="https://github.com/user-attachments/assets/0ce22f69-4444-4923-85c2-896217f7dcc5" height=150 width=150> <br/> **Android**| <img src="https://github.com/user-attachments/assets/5abd2834-0221-477f-a75e-ee580d22c1f0" height=150 width=150> <br/> **Android**|

</div>
<br>

## 개발 구조
<div align="center">
  <img src="https://github.com/user-attachments/assets/f731225f-c12c-4e32-bcf8-b08dc807b679" alt="제목을 입력해주세요" width="700" height="300">
</div>

## 개발 환경:
- Front : Android Studio JAVA (target sdk 32 / mid sdk 21)
- DB :  Firebase Storage , PHP 
- Web : Javascript

## 개발 기간 
- 전체 개발 기간 : 2022.12.01 ~ 2023.01.20
- 기능 구현 : 2022-12-01 ~ 2022-01-17

## H/W 구성
- 사용된 하드웨어
 ![Untitled](https://github.com/user-attachments/assets/aae4b825-618c-42b0-8ba9-4d790341c890)
  
- 하드웨어 회로도 구조
 ![다운로드](https://github.com/user-attachments/assets/e3a8d5f7-e481-4477-b7e7-647b202d947c)

## UI/UX
![Untitled (1)](https://github.com/user-attachments/assets/2d51f0b7-94b5-4870-9e80-1e738957fbe7)
<img src= "https://github.com/user-attachments/assets/841cce7e-0f9e-44ae-9bed-5d741f2c93cd"/>


## 트러블슈팅 
- **Web 와 App 간의 백엔드 작업**
      Web 와 App이 같은 DB를 활용해서 데이터를 수집하기 위해서는 백엔드 구현이 필요 <br>
    ⇒ (백엔드 PHP를 활용하여 DB 연결 및 쿼리문을 통한 데이터 수집 및 조회 기능 구현)

    
- **NFC 정보 읽어오는 문제**
    NFC 정보를 등록하기위해서는 NFC 등록 관련 이벤트가 필요 <br>
     ⇒ ( NFC 태그 접촉할시에 인텐트를 호출하여 해당 NFC UID를 불러옴 )<br>
     ⇒   ( 불러온 UID는 바이트로 되어있으므로 문자열로 파싱하여 UID 정보 저장)


## 개발툴
<img src="https://img.shields.io/badge/Android Studio-3DDC84?style=flat-square&logo=Android Studio&logoColor=white"/> <img src="https://img.shields.io/badge/java-007396?style=flat-square&logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=white"/> <img src="https://img.shields.io/badge/ESP32-323232?style=flat-square&logo=Espressif&logoColor=white"/> <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white"/>


