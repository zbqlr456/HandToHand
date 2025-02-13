# 🤝핸드 투 핸드 (Hand to Hand)

> **핸드 투 핸드 (Hand to Hand)** 는 우크라이나 기부를 독려하기 위한 프로젝트이며 다음과 같은 프로세스로 동작합니다.
> 1. 우크라이나 정부에 암호화폐를 기부할 수 있습니다.
> 2. 암호화폐를 기부하면 AI가 그린 우크라이나 풍경화 NFT를 받을 수 있습니다.
> 3. 리워드로 받은 NFT를 판매, 입찰, 구매할 수 있습니다.

## 🎥시뮬레이션

### 메인페이지
<div>
  <img src = "https://user-images.githubusercontent.com/63107888/224534981-b347b4f2-87af-43fd-9e9b-f842b4ffe756.gif">
</div>

### NFT 거래 페이지
<div>
  <img src = "https://user-images.githubusercontent.com/63107888/224535068-39c2050c-f4cd-4cdb-b5be-4717725c926c.gif">
</div>

<br />

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

## 📚기술 스택

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

## 💽시스템 아키텍처

<img src="./README.assets/architecture.PNG" alt="아키텍처(Architecture)" width="1000px" />

## 🔑ERD

<img src="./README.assets/erd.png" alt="개체-관계 모델(ERD)" width="1000px" />

<br />

## 👨‍💻나의 역할

### 팀원 공통
- 2주간의 서비스 기획을 통한 **회의록, 주제 선정, 세부 기능명세서, API 명세서, 와이어프레임**을 작성하였습니다.

### BlockChain Test Server 구현
- solidity, Node.js로 작성된 스켈레톤 코드를 참고하여 BlockChain, Backend의 Test Server를 구현하여 ERC서버의 동작원리를 시연하였습니다.

### ERD 다이어그램 설계
- DB에 저장될 데이터의 경계가 모호한 BlockChain과 Backend의 특성에 주의하여 ERD 다이어그램을 설계하였습니다.

### Backend 서버 구현
- Spring Data JPA를 활용한 DB와 Backend 서버를 구현하였습니다.

### NFT 거래 기능 개발
- NFT 판매 정보 등록, 조회, 취소, 완료와 구매자 정보를 업데이트하는 기능을 구현하였습니다.
