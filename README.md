# SYNC - Sketch Your Next Consumption
[디지털 하나로 금융 서비스 개발 2기]-2차 프로젝트

![image](https://github.com/user-attachments/assets/34e7517e-f0d5-41c8-a4ed-a062dcec945d)
> Sync는 생성형 AI를 활용한 그림일기 / 챌린지 기능을 통해 예금상품 활성화에 기여하는 프로젝트입니다.
<br/>

## 목차
[1. 프로젝트 개요](#1-프로젝트-개요)

[2. 기술 스택](#2-기술-스택)

[3. ERD](#3-erd)

[4. 서비스 아키텍처](#4-서비스-아키텍처)

[5. 기능 설명](#5-기능-설명)

[6. 팀원 소개](#6-팀원-소개)
<br/><br/><br/>

## 1. 프로젝트 개요
| 항목 | 내용 |
| --- | --- |
| 프로젝트 소개 | 생성형 AI를 활용한 MZ 뱅킹 서비스 |
| 개발 인원 | 총 4명 |
| 개발 기간 | 총 29일 (2024. 06. 13 ~ 2024 07. 11) |
<br/>

## 2. 기술 스택
| 기술               | 사용 |
|------------------| --- |
| Frontend         | <img src="https://img.shields.io/badge/react_native-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB"/> <img src="https://img.shields.io/badge/react-%2320232a.svg?style=flate&logo=react&logoColor=%2361DAFB"/> <img src="https://img.shields.io/badge/expo-1C1E24?style=flat&logo=expo&logoColor=#D04A37"/> <img src="https://img.shields.io/badge/-React%20Query-FF4154?style=flate&logo=react%20query&logoColor=white"/> |
| Backend        | <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat&logo=Spring Security&logoColor=white"> <img src="https://img.shields.io/badge/JWT-black?style=flate&logo=JSON%20web%20tokens">  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=Swagger&logoColor=black"> |
| Server           | <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat&logo=amazonec2&s&logoColor=white"> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=flat&logo=amazonrds&s&logoColor=white"> <img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=Flask&logoColor=white"> <img src="https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=flate&logo=apache-tomcat&logoColor=black"> |
| Database         | <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=Redis&logoColor=white"> |
| AI           | <img src="https://img.shields.io/badge/python-3776AB?style=flate&logo=python&logoColor=75befa"> <img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=OpenAI&logoColor=white"/> <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flate&logo=scikit-learn&logoColor=white"/> |

<br/>

## 3. ERD
![image](https://github.com/user-attachments/assets/42892882-a299-48bd-85ac-14cf4b8cad0d)


<br/><br/>

## 4. 서비스 아키텍처
![image](https://github.com/user-attachments/assets/1eb04726-cf85-4336-b876-6ee3c4ce7698)


<br/><br/>

## 5. 기능 설명
### ➊ 홈 & 마이페이지


<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><홈 화면></strong></td>
  </tr>
  <tr>
    <td  align="center">
       <img src="https://github.com/user-attachments/assets/9a3c66cd-bbc7-4a9e-9f93-447a8e9abec8" alt="홈화면" width="400">
    </td>
  </tr>
  <tr>
    <td>-'나의 챌린지 내역'과 '나의 그림일기 내역'으로 이동할 수 있습니다.<br/>-카드 선택 시, 해당 계좌의 상세 내역 조회 페이지로 이동합니다.<br/>-월별 계좌 사용 금액과 카테고리별 비율을 그래프로 시각화하여 확인할 수 있습니다</td>
  </tr>
</table>
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><마이페이지 화면></strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/1804903f-d8b6-4a7d-ae39-22d2005442d9" alt="홈화면" width="600">

    </td>
  </tr>
  <tr>
    <td>-프로필 변경 아이콘을 터치하면, 디바이스의 갤러리에서 사진을 불러옵니다. 사진을 선택하면 프로필 사진이 변경됩니다.<br/>-나의 챌린지 내역', '나의 그림일기 내역'으로 이동할 수 있습니다.<br/>-연락처, 주소, 연결된 계좌번호를 확인할 수 있습니다.<br/>-그림일기 생성에 필요한 크레딧의 개수를 표시합니다.</td>
  </tr>
</table>
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><계좌내역조회 화면></strong></td>
  </tr>
  <tr>
    <td align="center">
      사진 준비중입니다.
      <img src="https://github.com/user-attachments/assets/a2c5b460-dd84-46c0-9bf1-39b11a9d3f57" alt="홈화면" width="600">
    </td>
  </tr>
  <tr>
    <td>-카드 이미지 선택 시, 카드 정보를 확인할 수 있습니다.<br/>-연동된 계좌의 월별 사용 내역을 조회할 수 있습니다.</td>
  </tr>
</table>
<br/>



### ➋ 챌린지
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><챌린지 홈></strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/bfaea668-70c8-4f3b-a8cd-07acddffeb5a" alt="홈화면" width="600">
    </td>
  </tr>
  <tr>
    <td>- 챌린지 메인 화면입니다.<br/>-진행중인 챌린지와 주간 Hot 챌린지, 완료된를 확인할 수 있습니다.<br/>-진행중인 챌린지를 클릭하면 해당 챌린지의 상세 정보를 확인할 수 있습니다.
  </tr>
</table>
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong>&lt;챌린지 생성&gt;</strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/476af99c-cc8e-4080-bb7b-f7afadf67b3c" alt="홈화면" width="600">
    </td>
  </tr>
  <tr>
    <td>- 챌린지 생성 화면입니다.<br/>-원하는 챌린지를 생성하고 주변인들을 초대할 수 있습니다.<br/>-초대는 전화번호로 초대 / 최근 챌린지에 같이 참여한 사용자 초대를 진행할 수 있습니다.</td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/e9a55f29-f15e-4b96-8865-4a246df96f25" alt="홈화면" width="600">
    </td>
  </tr>
  <tr>
    <td>- 챌린지 생성 (2) 화면입니다.<br/>-챌린지에 참여한 사람들에게 맞는 AI 추천 카테고리를 확인할 수 있습니다.<br/>-챌린지 카테고리/기간/금액 등의 값 설정에 대한 투표를 진행할 수 있습니다.<br/>-챌린지 생성자인 방장은 참여자들의 의견을 보고 설정을 진행할 수 있습니다.</td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/ac4518f3-b2d0-4a7a-b0f3-62bdf93dc130" alt="홈화면" width="600">
    </td>
  </tr>
  <tr>
    <td>- 챌린지 생성 (3) 화면입니다.<br/>-설정이 끝나면 해당 설정으로 챌린지를 시작할 것인지 최종적으로 확인할 수 있습니다.<br/>-방장에게는 참여자들의 수락 현황이 표시되고<br/>참여자들에게는 챌린지 정보 및 수락/거절 화면이 표시됩니다.</td>
  </tr>
</table>
<br/>

### ➌ 그림일기
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong>&lt;그림일기 생성&gt;</strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/1385c842-8a24-4e49-a677-55f1b4fb0bef" alt="생성 화면" width="600">
    </td>
  </tr>
  <tr>
    <td>-최근 소비내역을 가져와 그림일기 소재로 사용할 소비내역을 자유롭게 선택할 수 있습니다.<br/>-선택된 소비내역을 바탕으로 키워드를 생성할 수 있습니다. 생성된 키워드를 수정하거나, 임의로 다른 키워드를 추가할 수 있습니다.<br/>-유화, 동양화, 일본 애니메이션, 귀여움, 캐리커쳐 등 총 8가지의 그림체 중 원하는 그림체를 선택할 수 있습니다.</td>
  </tr>
    <tr>
    <td align="center" style="vertical-align: middle;"><strong>&lt;그림일기 확인/다시 그리기&gt;</strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/dd4b2f0b-a289-46f3-88ac-6ac356422aa2" alt="결과 화면" width="600">
    </td>
  </tr>
  <tr>
    <td>-생성된 그림일기 결과값을 볼 수 있습니다.<br/>-그림이 마음에 들지 않으면, 다시 그리기를 통해 앞서 설정한 소비내역/키워드를 바탕으로 다시 그림을 그려볼 수 있습니다.<br/>-일기가 마음에 들면, 확정하기를 통해 디바이스에 결과물을 저장하고, SNS를 통해 주변인들과 자신의 그림일기를 공유할 수 있습니다.</td>
  </tr>
</table>
<br/>


### [🖥️ 시연 영상](https://www.youtube.com/watch?v=CE3quElE-sY)
<br/>

## 6. 팀원 소개
<table>
    <tr align="center">
        <td><B>김서윤</B></td>
        <td><B>남우현</B></td>
        <td><B>임태규</B></td>
        <td><B>한원희</B></td>
    </tr>
    <tr align="center">
        <td>
            <img src="https://github.com/yunred.png?size=100" width="100">
            <br>
            <a href="https://github.com/yunred"><I>yunred</I></a>
        </td>
        <td>
            <img src="https://github.com/hikiman9.png?size=100" width="100">
            <br>
            <a href="https://github.com/hikiman9"><I>hikiman9</I></a>
        </td>
        <td>
            <img src="https://github.com/bigstar9906.png?size=100" width="100">
            <br>
            <a href="https://github.com/bigstar9906"><I>bigstar9906</I></a>
        </td>
        <td>
            <img src="https://github.com/Wonhee0221.png?size=100" width="100">
            <br>
            <a href="https://github.com/Wonhee0221"><I>Wonhee0221</I></a>
        </td>
    </tr>
</table>
