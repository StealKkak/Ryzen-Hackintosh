# AMD 라이젠 해킨토시

![macOS](https://img.shields.io/badge/Sequoia-15.1-informational.svg)  
![OpenCore](https://img.shields.io/badge/OpenCore-1.0.2-informational.svg)

## 테스트 버전
macOS Sequoior 15.1  
OpenCore 1.0.2

## 사양 정보
|구분      |모델|비고|
|---------|----|----|
|CPU|AMD Ryzen 3400G with Radeon Vega Graphics| |
|M/B|GIGABYTE B450M DS3H(rev. 1.x)| |
|쿨러|Wraith Stealth Cooler|Ryzen 번들 쿨러|
|SSD0|Samsung PM981 512GB|Windows 전용|
|SSD1|MX500 256GB|macOS 디스크|
|GPU0|NVIDIA GeForce RTX 2060 6GB|비활성화|
|GPU1|AMD Radeon(TM) RX Vega 11 Graphics|iGPU|
|Wifi|IPTIME A3000U|macOS와 호환되지 않음
|Bluetooth|CSR 4.0 Bluetooth||

## 작동하는 것
 * iCloud  
 * Bluetooth  
 * 사운드  
 * 이더넷  
 * iMessage & Facetime  
 * 그래픽 가속  
 * 잠자기

## 작동하지 않는 것
* Wi-Fi  
* iCloud로 연동된 AirPods  
* Airdrop, Hand-off 등을 포함한 연속성 기능(Wi-Fi 네이티브 연결 요구)  
* 아이폰 미러링(T2 보안칩 요구)  
* About This Mac CPU 정보 수정

## Kext
 * WIP
