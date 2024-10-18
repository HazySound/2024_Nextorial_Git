# 2024 넥토리얼 포트폴리오 Git - 박시몬   

## 🏷️ 기본 정보
**Title :** NotMyFall-t   
**Used tool :** Unity, Visual Studio 2019, GitHub, Discord   
**Content :**   
>본 프로젝트는 일명 ‘항아리 게임’이라 불리는 <Getting Over It with Bennett Foddy> 와 <Only Up!> 과 같은 작품들과 유사한 장르의 플랫포머 멀티 게임으로, 두 명이 한 로봇의 좌, 우를 각각 조종하여 장애물을 피해 목적지까지 도달하는 게임입니다.   
>
>각 플레이어는 자신이 담당하고 있는 반신의 손과 발에서 불꽃을 뿜어낼 수 있으며, 로봇은 그 추진력을 통해 비행합니다.
>
>손과 발의 각도는 각각 마우스, 키보드로 조절하며 좌클릭과 스페이스바를 이용하여 비행할 수 있습니다.
>
>비행 도중 장애물에 맞거나 연료가 떨어지면 추락하게 되며, 발판에 안정적으로 착지하기 전까지 조종 불가 상태가 되어 시작 지점까지 떨어지는 일도 얼마든지 발생할 수 있습니다.
   
   
## 💻 작성 및 참여한 파트   
* 게임 기획
* 캐릭터 조종(팔다리 움직임 및 이동) 구현
* 일부 함정 및 장애물 구현(얼음 발판, 독수리, 버드 스트라이크 등)
* BGM, 효과음, 음성 등의 자료 준비 및 실행 구현
* 음성 재생 시 자막 표시 기능 구현
   
   
## 📂 기여한 Script 기본 경로 및 클래스명
**1. 캐릭터 조종 기본 경로:** 
```
\Assets\Script\SimonPark_Scripts\Controller\
```
**팔다리 움직임 구현 :** PlayerController.cs   
**이동 관련 기능들 구현 :** JetController.cs   
   
---
**2. 음성/음악파일 재생 및 자막 출력 기본 경로 :** 
```
\Assets\Script\SimonPark_Scripts\Audio&Subtitle\
```
**음원 재생 구현 :** VoiceManager.cs   
**자막 출력 구현 :** SubtitleManager.cs   
   
---
**3. 함정 및 장애물 기본 경로 :** 
```
\Assets\Script\SimonPark_Scripts\Obstacles\
```
**얼음 발판 구현 :** CheckIce.cs, IceCube.cs   
**팔 부스터 제한 구현** : ArmBrokenTrigger   
**독수리 함정 구현 :** EagleShot.cs, EagleContainer.cs  (EagleCollider.cs의 경우 효과음 재생을 위한 충돌체 스크립트)   
**버드 스트라이크 구현 :** BirdArea.cs, BirdStrike.cs   
   
   
## [📹 시연 영상 (2023 포톤잼 출품 당시 제출 영상 Youtube Link)](https://www.youtube.com/watch?v=jTH2MDyW_-o)   
