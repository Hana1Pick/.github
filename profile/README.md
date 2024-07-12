# 하나원픽
[디지털 하나로 금융 서비스 개발 2기]-2차 프로젝트

![hana1pickposter](https://github.com/user-attachments/assets/1c5b3580-54a9-4f55-873c-92edd1932386)
> 하나원픽은 국내외 MZ세대를 대상으로 차별화된 기록통장, 모임통장 등의 다양한 금융 상품을 제공하는 서비스입니다.
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
| 프로젝트 소개 | MZ 맞춤 최애 금융 서비스, 하나원픽 |
| 개발 인원 | 총 5명 |
| 개발 기간 | 총 29일 (2024. 06. 13 ~ 2024 07. 11) |
<br/>

## 2. 기술 스택
| 기술               | 사용 |
|------------------| --- |
| Frontend         | <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=TypeScript&logoColor=white"/> <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=React&logoColor=black"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white"/> <img src="https://img.shields.io/badge/WebRTC-333333?style=flat&logo=webrtc&logoColor=white"/> |
| Backend        | <img src="https://img.shields.io/badge/java-007396?style=flat&logo=java&logoColor=white"/> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=Swagger&logoColor=black"> |
| Database         | <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white"> <img src="https://img.shields.io/badge/Redis-DC382D?style=flat&logo=Redis&logoColor=white"> |
| Deploy           | <img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=flat&logo=amazonec2&s&logoColor=white"> <img src="https://img.shields.io/badge/NGINX-009639?style=flat&logo=nginx&s&logoColor=white"> <img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&s&logoColor=white"> |
| Amazon           | <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=flat&logo=amazonrds&s&logoColor=white"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=flat&logo=amazons3&s&logoColor=white"> |
| API              | <img src="https://img.shields.io/badge/Naver Cloud-03C75A?style=flat&logo=Naver Cloud&logoColor=black"/> <img src="https://img.shields.io/badge/DeepL-0F2B46?style=flat&logo=deepl&logoColor=white"/> |
| Cooperative Tool | <img src="https://img.shields.io/badge/github-181717?style=flat&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=flat&logo=git&logoColor=white"> |
| IDE              | <img src="https://img.shields.io/badge/Visual Studio Code-007ACC?style=flat&logo=Visual Studio Code&logoColor=white"/> <img src="https://img.shields.io/badge/intellijidea-000000?style=flat&logo=intellijidea&logoColor=white"> |
<br/>

## 3. ERD
<img src="https://github.com/user-attachments/assets/e627a5e8-e69f-4f1b-bcdb-f04663e11898" width="75%"/>

<br/><br/>

## 4. 서비스 아키텍처
<img src="https://github.com/user-attachments/assets/5afb0c65-3a4d-4490-bd8d-133e3d189707" width="70%"/>

<br/><br/>

## 5. 기능 설명
### ➊ 회원가입 및 비대면 계좌 개설

<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><내국인></strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/dbb154f0-cadc-4b7e-a1b3-0d52da0b2485" alt="내국인 회원가입">
    </td>
  </tr>
  <tr>
    <td>- 카카오톡 계정으로 회원가입이 가능합니다.<br/>- 간편 인증 절차를 통해 쉽게 본인 확인을 진행할 수 있습니다.<br/>- 인증 패턴 등록 후 간편하게 상품 가입 및 거래를 진행할 수 있습니다.</td>
  </tr>
</table>
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><외국인></strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/13b07b03-cbee-48c5-8684-60d70a3aaac2" alt="외국인 회원가입">
    </td>
  </tr>
  <tr>
    <td>- 국내 거주 외국인은 외국인 등록증 인증을 통해 본인 확인이 가능합니다.</td>
  </tr>
</table>

<br/>

### ➋ 계좌이체 및 QR 송금
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong><계좌이체></strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/14c6a7da-4cce-40dd-a4a5-0596f74d4ac9" alt="계좌이체">
    </td>
  </tr>
  <tr>
    <td>- 거래내역을 바탕으로 최근 송금한 계좌 목록이 표시됩니다.<br/>- 이름 또는 계좌번호 검색을 통해 송금 계좌를 조회할 수 있습니다.<br/>- 출금 가능 금액 내에서 이체할 금액을 버튼 터치만으로 쉽게 설정할 수 있습니다.</td>
  </tr>
</table>
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong>&lt;QR 송금&gt;</strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/47c95918-3a49-44a7-a738-211489cfbbbb" alt="QR송금">
    </td>
  </tr>
  <tr>
    <td>- 받고자 하는 금액을 입력하면 해당 계좌의 QR코드가 생성되고 저장이 가능합니다.<br/>- QR 송금 시 QR에 설정된 계좌번호와 금액으로 계좌이체가 이루어집니다.<br/>- 입금 계좌번호의 최근 3개월 간 거래내역 조회를 통해 위험 계좌인지 확인이 가능합니다.</td>
  </tr>
</table>
<br/>

### ➌ 셀럽로그
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong>&lt;셀럽로그&gt;</strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/f6de4114-c78a-4264-9179-efe4a0f54810" alt="셀럽로그 생성">
    </td>
  </tr>
  <tr>
    <td>- 원하는 연예인과 출금 계좌를 선택한 뒤 계좌 이름을 입력하면 셀럽로그 개설이 완료됩니다.</td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/5fbbca77-7487-4ad8-9322-d66e0f123e70" alt="셀럽로그 부가">
    </td>
  </tr>
  <tr>
    <td>- 계좌 조회 시 좋아하는 최애의 사진을 볼 수 있습니다.<br/>- 나만의 입금 규칙을 자유롭게 설정할 수 있습니다.<br/>- 입금할 규칙과 관련 해시태그를 선택하면 쉽고 빠르게 입금이 가능합니다.<br/>- 계좌 커버 사진도 변경 가능합니다.</td>
  </tr>
</table>
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong>&lt;포토카드&gt;</strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/4fb885e7-743f-4362-94c3-7989a7be3e3b" alt="포토카드">
    </td>
  </tr>
  <tr>
    <td>- 원하는 스티커를 선택하면 좋아하는 연예인과 사진을 함께 찍을 수 있습니다.<br/>- 내 사진과 좋아하는 연예인 사진을 선택하면 합성 포토카드가 완성됩니다.</td>
  </tr>
</table>
<br/>

### ➍ 모아클럽
<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/d07be205-347d-4712-bba0-66a8b3c7d46d" alt="여러통화">
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/f6d23a73-d540-48e9-867c-d9745be7eb1c" alt="모임원관리">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/34011bd6-47f5-4534-a025-95f01fd0f923" alt="투표기능">
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/312672fe-a8ef-48a3-b260-6b384d33fc01" alt="자동이체">
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/1b3f622d-7b0e-4c8a-b964-d153afd79f34" alt="외화거래">
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/a187ef65-6326-42ee-ae87-2064f2bf9acb" alt="환전수수료">
    </td>
  </tr>
</table>
<table>
  <tr>
    <td align="center" style="vertical-align: middle;"><strong>&lt;다국어 지원&gt;</strong></td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/ccd5e88e-0282-4bab-8f76-5c1d988d5a4d" alt="다국어">
    </td>
  </tr>
  <tr>
    <td>- 회원가입 시 등록된 국적으로 모든 페이지 번역을 제공합니다.<br/>- 실시간 번역 채팅을 통해 국적이 서로 다른 모임원들 간의 원활한 소통을 지원합니다.</td>
  </tr>
</table>
<br/>

### [🖥️ 시연 영상](https://youtu.be/hChAfqNkoO8)
<br/>

## 6. 팀원 소개
<table>
    <tr align="center">
        <td><B>김가원</B></td>
        <td><B>김주혜</B></td>
        <td><B>박소연</B></td>
        <td><B>유다영</B></td>
        <td><B>유민아</B></td>
    </tr>
    <tr align="center">
        <td>
            <img src="https://github.com/kgw0124.png?size=100" width="100">
            <br>
            <a href="https://github.com/kgw0124"><I>kgw0124</I></a>
        </td>
        <td>
            <img src="https://github.com/juhyemi.png?size=100" width="100">
            <br>
            <a href="https://github.com/juhyemi"><I>juhyemi</I></a>
        </td>
        <td>
            <img src="https://github.com/soyeonvv.png?size=100" width="100">
            <br>
            <a href="https://github.com/soyeonvv"><I>soyeonvv</I></a>
        </td>
        <td>
            <img src="https://github.com/allzeroyou.png?size=100" width="100">
            <br>
            <a href="https://github.com/allzeroyou"><I>allzeroyou</I></a>
        </td>
        <td>
            <img src="https://github.com/minahyou.png?size=100" width="100">
            <br>
            <a href="https://github.com/minahyou"><I>minahyou</I></a>
        </td>
    </tr>
</table>
