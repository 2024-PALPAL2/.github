# iot-repo-3
IoT 프로젝트 3조 저장소. 팔팔이
---
> ### IoT 기술 기반 스마트 물류 시스템을 구현합니다. 물류 자동화 및 센서 기반 물류 상태 실시간 모니터링을 제공합니다.

<br />

## 🤖 프로젝트 소개
<details markdown="1">
  <summary><h3>Iot 기반 스마트 물류 시스템</h3></h3></summary>
  <li>물류 산업은 점차 대형화, 복잡화되고 있으며, 효율적인 운영 체계 구축이 필수적인 과제로 대두되고 있다.</li>
  <li>본 프로젝트는 IoT 센서, 실시간 데이터에 기반하여 물류 프로세스 자동화를 목표로 한다.</li>
  <li>제안된 시스템은 물류 관리의 최적화와 자원 활용 효율성을 향상시킬 수 있을 것으로 기대된다.</li>
</details>
<br />

## 🧠 구성원 및 역할
|이름|업무|
|:---|:---|
|임시온|- 데이터베이스 설계 및 구현<br> - PyQT UI 구현 <br> - git 관리|
|최희재|- 컨베이어 구동 기능 구현<br>-택배 감지 및 분류 기능 구현<br> - 시스템 구성도 설계|
|조나온|- QR 코드 인식 기능 구현<br> - 시퀀스 다이어 그램 제작<br> - Confluence 문서 관리|
|김진재|- Serial 통신 구현<br> - UI base code 제작 <br> - 모니터링 기능 구현|
|문세희|- 프로젝트 운영 및 관리|
<br />

## 🖥️ 활용 기술
|구분|상세|
|:---|:---|
|개발환경|<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white" /> |
|IDE| <img src="https://img.shields.io/badge/VSCode-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white" /> <img src="https://img.shields.io/badge/arduino-00878F?style=for-the-badge&logo=arduino&logoColor=white" /> |
|언어| <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" /> <img src="https://img.shields.io/badge/c++-00599C?style=for-the-badge&logo=c++&logoColor=white" /> |
|DB|<img src="https://img.shields.io/badge/Amazon_RDS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" /> <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" />|
|협업| <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white" /> <img src="https://img.shields.io/badge/confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white" /> <img src="https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" /> <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white" />||
<br />

#### Hardware
    제어 보드 : arduino uno
    사용 언어 : cpp
    
    (사용 센서)
    - CMOS QR 코드 스캐너 모듈 2D Barcode Scanner USB
    - 2A L298 모터드라이버 모듈
    - 28BYJ-48 ULN2003 Step Moter
    - ULN2003 Step Moter Driver
    - 기어박스장착모터 (NP01D-288)
    - TCRT5000 적외선 IR 센서
    
    (통신 방식)
    - Serial 통신

#### PC
    사용 언어 : Python

    사용 모듈 : Serial, Pyqt5,, requests, threading
