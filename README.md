# SOCAT

소소코인을 모아 고양이를 키우자.

블록체인 기반 P2E 웹 게임.

## Summary.



### 낚시 게임

낚시 게임은 개별적으로 움직이는 5마리의 물고기를 상하좌우로 움직이는 낚시대를 이용하여 잡는 react 기반 게임임. 

물고기 움직임의 방향을 매번 랜덤하게 만들기 위해 setInterval 과 Math.random() 을 사용하였음.

구매한 낚시대에 따라 물고기가 잡히는 범위를 state로 조정하였음.


### 낚시대 뽑기


### 거래소


## Implementation.

### Backend

백엔드는 이더리움 블록체인 네트워크에 배포하는 것으로 가정하고 진행하였음.

비용문제로 실제 이더리움 메인 네트워크에 배포하지 않고 ropsten test network에 배포하는 것을 목표로 하였으나, eth send transaction 문제로 진행하지 못하였고, 로컬에 배포하여 테스트하였음.

코인은 [openzeppelin]("https://github.com/OpenZeppelin/openzeppelin-contracts")의 ERC20을 상속하여 게임 기능에 맞게 수정하여 작성하였음.

contract를 처음 배포한 노드를 owner 계정으로 설정하여, 최초 발행된 코인을 지급하며, 유저들이 게임플레이를 통하여 owner로부터 코인을 지급받는 방식.

이더리움은 contract에 전송하고 받는 방식을 취함 

게임 전체는 CatBase Solidity Contract를 통해 클라이언트와 상호작용할 수 있도록 하였음.



### Frontend


## Made By.

[부산대학교 정보컴퓨터공학부 18학번 이제호](https://github.com/jhl8109)

[성균관대학교 소프트웨어학과 20학번 김선우](https://github.com/Sunwoo0110)


[KAIST 전산학부 17학번 권기훈](https://www.github.com/kyoonkwon)
