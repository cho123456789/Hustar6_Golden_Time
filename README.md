# **미아 빙지 프로젝트**
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
- Web : Springboot

## 개발 기간 
- 전체 개발 기간 : 2022-10-05 ~ 2022-11-05
- 회의 :  2022-10-11 ~ 2022-10-29 ((주)디월드 전무이사님 멘토링) 
- 기능 구현 : 2022-10-10 ~ 2022-11-04

## 모델링 
- 데이터셋 구성
![image](https://github.com/user-attachments/assets/4b1ee16b-39b2-44a1-9ce0-89de0fd1661d)
![image](https://github.com/user-attachments/assets/8048473c-87e8-4caf-90ea-1a5e308e768c)

## 학습코드 
https://github.com/cho123456789/Hustar-BMK-Yolov5

## 패이지별 기능

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/d4ed2685-19f4-49de-9257-f39e5ea26b43" alt="splash" width="300"/></td>
    <td>
      <h3>초기화면</h3>
      <ul>
        <li>splash 화면이 잠시 나온 뒤 다음 페이지가 나타납니다.</li>
        <li>사용자 정보를 넣고 <b>책반납버튼</b>을 누르면 반납이 시작됩니다</li>
        <li>로그인 기능은 구현되어 있지 않습니다.</li>
      </ul>
    </td>
  </tr>
</table>


<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/8cf62ff1-6661-40b6-9690-ecaafc93123c" alt="splash" width="300"/></td>
    <td>
      <h3>바코드스캔</h3>
      <ul>
        <li>카메라 촬영버튼을 통해서 책에 있는 바코드를 스캔합니다</li>
        <li><b>업로드 버튼</b>을 통해 바코드에 있는 책에 대한 정보를 불러옵니다</li>
        <li>바코드 인식 개선 문제로 숫자로 대체하였습니다.</li>
      </ul>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/20b6d594-4bba-44a3-936a-4a5c99cf281e" alt="splash" width="303"/></td>
    <td>
      <h3>책 촬영</h3>
      <ul>
        <li>카메라 촬영버튼을 통해서 책을 스캔합니다.</li>
        <li><b>업로드 버튼</b>을 통해서 책의 이미지정보를 전송합니다.</li>
        <li>이미지 정보를 학습이 완료된 Yolov5모델에 테스트를 진행합니다.</li>
      </ul>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/d68bca12-193f-413e-875a-081f070f8fa9" alt="splash" width="303"/></td>
    <td>
      <h3>책 훼손여부 파악</h3>
      <ul>
        <li>책 이미지를 통해서 훼손 여부에 대한 이미지 정보를 불러옵니다.</li>
        <li><b>줌인기능</b>을 토대로 훼손여부를 파악합니다.</li>
      </ul>
    </td>
  </tr>
</table>

## 개발툴
<img src="https://img.shields.io/badge/Android Studio-3DDC84?style=flat-square&logo=Android Studio&logoColor=white"/> <img src="https://img.shields.io/badge/java-007396?style=flat-square&logo=java&logoColor=white"/>
<img src="https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=white"/>
