<div align="center">
  <h1>핸드 투 핸드 (Hand to Hand)</h1>
  <br/>
</div>

## 💁 웹 서비스 소개

**핸드 투 핸드 (Hand to Hand)** 는 우크라이나 기부를 독려하기 위한 프로젝트입니다.

1. 우크라이나 정부에 암호화폐를 기부할 수 있습니다.
2. 암호화폐를 기부하면 AI가 그린 우크라이나 풍경화 NFT를 받을 수 있습니다.
3. 리워드로 받은 NFT를 판매, 입찰, 구매할 수 있습니다.

## Simulation

### 메인페이지
<div>
  <img src = "https://user-images.githubusercontent.com/63107888/224534981-b347b4f2-87af-43fd-9e9b-f842b4ffe756.gif">
</div>

### NFT 거래 페이지
<div>
  <img src = "https://user-images.githubusercontent.com/63107888/224535068-39c2050c-f4cd-4cdb-b5be-4717725c926c.gif">
</div>

<br />

## 🛠 기술 스택

### **Front-end**

| <img src="https://profilinator.rishav.dev/skills-assets/html5-original-wordmark.svg" alt="HTML5" width="50px" height="50px" /> | <img src="https://profilinator.rishav.dev/skills-assets/css3-original-wordmark.svg" alt="CSS3" width="50px" height="50px" /> | <img src="https://profilinator.rishav.dev/skills-assets/javascript-original.svg" alt="TypeScript" width="50px" height="50px" /> |
| :----------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------: |
|                                                             HTML5                                                              |                                                             CSS3                                                             |                                                           javascript                                                            |

| <img src="https://profilinator.rishav.dev/skills-assets/vuejs-original-wordmark.svg" alt="React.js" width="50px" height="50px" /> | <img src="https://user-images.githubusercontent.com/7110136/29002857-9e802f08-7ab4-11e7-9c31-604b5d0d0c19.png" alt="vuex" width="50px" height="50px" /> | <img src="https://seeklogo.com/images/W/web3js-logo-62DEE79B50-seeklogo.com.png" alt="web3js" width="50px" height="50px" /> | <img src="https://getbootstrap.com/docs/5.0/assets/brand/bootstrap-logo.svg" alt="bootstrap" width="60px" height="50px"> |
| :-------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------: |
|                                                                Vue                                                                |                                                                          Vuex                                                                           |                                                           web3.js                                                           |                                                        Bootstrap                                                         |

### **Blockchain**

| <img src="https://trufflesuite.com/assets/logo.png" alt="bootstrap" width="50px" height="50px"> |
| :---------------------------------------------------------------------------------------------: |
|                                           truffle.js                                            |

### **AI**

| <img src="https://pytorch.org/assets/images/pytorch-logo.png" alt="bootstrap" width="50px" height="50px"> |
| :-------------------------------------------------------------------------------------------------------: |
|                                                  PyTorch                                                  |

### **Back-end**

| <img src="https://profilinator.rishav.dev/skills-assets/java-original-wordmark.svg" alt="Java" width="50px" height="50px" /> | <img src="https://www.seekpng.com/png/full/8-80775_spring-logo-png-transparent-spring-java.png" alt="Spring-Boot" width="50px" height="50px" /> | <img src="https://profilinator.rishav.dev/skills-assets/mysql-original-wordmark.svg" alt="MySQL" width="50px" height="50px" /> |
| :--------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------: |
|                                                             Java                                                             |                                                                   Spring-Boot                                                                   |                                                             MySQL                                                              |

### **DevOps**

| <img src="https://profilinator.rishav.dev/skills-assets/nginx-original.svg" alt="NGiNX" width="50px" height="50px" /> | <img src="https://pbs.twimg.com/profile_images/1351702967561252865/aXfcETIt_400x400.jpg" alt="aws" width="50px" height="50px" /> | <img src="https://profilinator.rishav.dev/skills-assets/docker-original-wordmark.svg" alt="docker" width="50px" height="50px" /> |
| :-------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------: |
|                                                         NGiNX                                                         |                                                               aws                                                                |                                                              docker                                                              |

<br />

<div id="3"></div>

## 💡 주요 기능

| 기능           | 내용                                                                  |
| :------------- | :-------------------------------------------------------------------- |
| 지갑 연결      | 개인 키를 입력하여 지갑을 연결할 수 있습니다.                         |
| 기부           | 연결된 지갑의 잔액을 조회하고, 잔액 미만의 금액을 기부할 수 있습니다. |
| 기부 내역 확인 | 나의 기부 내역을 확인할 수 있습니다.                                  |
| NFT 발급       | 나의 기부 내역에서 NFT를 발급 받을 수 있습니다.                       |
| NFT 조회       | 다른 사람들의 NFT, 내가 보유한 NFT를 조회할 수 있습니다.              |
| NFT 거래       | NFT를 판매, 입찰, 구매할 수 있습니다.                                 |

<br />

<div id="4"></div>

## 📂 프로젝트 구성도

|                                   아키텍처(Architecture)                                   |
| :----------------------------------------------------------------------------------------: |
| <img src="./README.assets/architecture.PNG" alt="아키텍처(Architecture)" width="1000px" /> |

|                              개체-관계 모델(ERD)                               |
| :----------------------------------------------------------------------------: |
| <img src="./README.assets/erd.png" alt="개체-관계 모델(ERD)" width="1000px" /> |

<br />

<br />

- |  이름  |            역할            | <div align="center">개발 내용</div>                          |
  | :----: | :------------------------: | :----------------------------------------------------------- |
  | 김응철 |          Backend           | - Test Server 구현<br />- DB 설계 <br />- JPA 구조 설계<br />- 판매API<br/>    &nbsp; - 판매 정보 등록 API<br/>  &nbsp; - 판매 조회 API<br /> &nbsp; - 판매 취소 API<br />  &nbsp; - 판매 완료 API<br />  &nbsp; - 구매자 정보 업데이트 API |
  | 유현수 |   Frontend & Blockchain    | - 지갑 연결 및 회원관리 <br /> - 잔액 확인 및 송금 <br /> - 송금 내역 조회 <br /> - NFT 발급 <br /> - 내 NFT 조회 <br /> - API 호출 모듈 <br />- web3 트랜잭션 모듈 <br /> - vuex, Router |
  | 이상백 | AI & Blockchain & Frontend | **1. [블록체인] 스마트 컨트랙트 설계 <br />** A. HandToHand 개별 토큰 개발 (HTH, ERC-20)<br /> 1) `Ownable` 도입으로 토큰의 발행 주체 단일화<br /> 2) Gas 비용 절감을 위한 조회용 `view` 함수 조회<br /> 3) 송금에 중간 개입자 개입을 위한 `approve` 함수 구현<br /><br /> B. NFT 개발 (ERC-721)<br /> 1) 토큰 발행 주체의 단일화<br /> 2) 조회용 `view` 함수 구현 (NFT 정보 조회시 Gas 비용 절감)<br /> 3) NFT 이전에 중간 개입자 개입을 위한 `approve` 함수 구현<br /><br /> C. 서비스 개별 토큰(HTH)을 이용한 NFT 거래 플랫폼 개발<br /> 1) `SaleFactory` 컨트랙트 도입 및 `Sale` 주체 단일화<br /> 2) NFT 입찰 및 판매에 생성되는 Sale 컨트랙트 구현<br /> 3) 각 동작별 분기처리를 위한 `Modifier` 함수 구현<br /> 4) 입찰, 판매 동작시 log 기록을 위한 `Event` 함수 구현<br /><br /> **2. [인공지능] Deep Learning 모델 설계<br />** A. 목표 결과물 설정<br /> 1) 우크라이나의 풍경화, 도시화 학습 모델 설정<br /> 2) style 변수를 입힌 GAN 모델 모색, StyleGAN3 모델 설정<br /><br /> B. Training 데이터 수집<br /> 1) 우크라이나 자연 및 도시 풍경 Crawling 이미지 (약 3,000 개)<br /> 2) WikiArt cityscape image (약 5,000 개)<br /> 3) WikiArt landscape image (약 5,000 개)<br /><br /> C. GAN 모델 학습<br /> 1) 1차 학습 : `gamma=8.2`, 약 4-5 일 학습 진행<br /> 2) 2차 학습 : `gamma=6.6`, 약 1-2 일 학습 진행<br /><br /> D. 결과물 도출 및 검증<br /> 1) 학습 모델 활용 이미지 생성 (약 2,600개)<br /> 2) `FID` 값 10~11 에 수렴<br /> 3) `kimg` 값 4500~5000 도달<br /><br /> **3. [프론트] NFT 거래 페이지 구현<br />** A. Front <=> SSAFY 네트워크 (블록체인) 연결<br /> 1) 블록체인 연결에 Web3 라이브러리 도입<br /> 2) Front 에서 `approve` 권한 구현<br /><br /> B. NFT 판매, 입찰 동작 구현<br /> 1) 스마트 컨트랙트 함수 기반의 판매, 입찰 동작 구현<br /> C. NFT 거래 내역 기록<br /> 1) 스마트 컨트랙트 동작 후, 서비스 개별 DB 에 기록 |
  | 정은이 |       Backend & 팀장       | - Test Server 구현<br />- DB 설계<br />- JPA 구조 설계<br />- Spring Boot S3 연결<br/> - 기부 API<br/>  &nbsp; - 기부 요청 API<br/>  &nbsp; - 기부 상태 업데이트 API<br />  &nbsp; - 기부 조회 API<br />\- 작품 API<br/>  &nbsp; - 파일 업로드 API<br/>  &nbsp; - 작품 지급 API<br/>  &nbsp; - 작품 정보 업데이트 API<br /> &nbsp; - 작품 상세 조회 API<br />\- 회원API<br/>  &nbsp; - 지갑 연동 API<br/> &nbsp; - 닉네임 변경 API |
  | 황승연 |          Backend           | 1.백엔드<br /> -전체 작품 목록 조회 API 구현<br/> -특정 wallet address가 보유한 작품 목록 조회API 구현<br/> -판매중인 작품 목록 조회 API 구현<br /> -좋아요 업데이트 API 구현<br/> 2.서버 및 배포<br/> -AWS EC2 서버 세팅 <br/> -AWS EC2와 Docker 활용한 DB 구축<br/> -Docker 활용한 SpringBoot 배포<br/> -Nginx 수동 배포 |


## 📅 개발 기간

22.02.21. ~ 22.04.08
