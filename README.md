# 🤖 WINGBOT: Autonomous Reconnaissance Mission Robot Platform

<div align="center">

| |
| :---: |
| <img src="https://github.com/user-attachments/assets/7540d939-b5b8-45a9-aab8-837171949385" alt="WINGBOT Hero Image" width="100%"/> |
| **🚀 AI 기반 자율 정찰 로봇 WINGBOT**<br> 연구, 교육, 실전 경진대회까지 활용 가능한 통합 솔루션 |

</div>

---

## 📌 1. Overview

본 플랫폼은 **Edge AI 기반 자율주행 로봇 개발**과 **Physical AI 교육**을 위한 최적의 통합 환경을 제공합니다. 하드웨어와 소프트웨어를 아우르는 올인원 플랫폼으로, 실제 로봇 기반의 AI 기술 고도화를 지원합니다.

<table width="100%" style="table-layout: fixed; width: 100%; border-collapse: collapse;">
  <tr>
    <td width="50%" valign="top" style="border: 1px solid #e1e4e8; padding: 20px;">
      <h3 align="left">🚀 Edge AI 기반 자율주행</h3>
      <ul>
        <li>실시간 영상 처리 및 객체 인식</li>
        <li>자율 주행 및 장애물 회피</li>
        <li>센서 융합 기반 판단 시스템</li>
      </ul>
    </td>
    <td width="50%" valign="top" style="border: 1px solid #e1e4e8; padding: 20px;">
      <h3 align="left">🧠 AI 교육 최적화 플랫폼</h3>
      <ul>
        <li>Python 기반 AI 학습 환경</li>
        <li>Jupyter Notebook 실습 지원</li>
        <li>초급 ~ 고급 단계별 커리큘럼</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top" style="border: 1px solid #e1e4e8; padding: 20px;">
      <h3 align="left">🛠️ Physical AI 통합 구조</h3>
      <ul>
        <li>하드웨어 + 소프트웨어 통합 설계</li>
        <li>실제 로봇 기반 실습 가능</li>
        <li>산업/국방형 시나리오 대응</li>
      </ul>
    </td>
    <td width="50%" valign="top" style="border: 1px solid #e1e4e8; padding: 20px;">
      <h3 align="left">🏁 경진대회 및 연구 활용</h3>
      <ul>
        <li>AI 자율주행 대회 대응</li>
        <li>국방/로봇 경진대회 활용 가능</li>
        <li>실전 문제 해결 중심 설계</li>
      </ul>
    </td>
  </tr>
</table>

<br>

<div align="center">
  <img src="https://github.com/user-attachments/assets/e25df7e8-9657-4f91-bfc3-01e9f56fc80b" width="24%" style="margin: 0 0.5%;"/>
  <img src="https://github.com/user-attachments/assets/e25df7e8-9657-4f91-bfc3-01e9f56fc80b" width="24%" style="margin: 0 0.5%;"/>
  <img src="https://github.com/user-attachments/assets/e25df7e8-9657-4f91-bfc3-01e9f56fc80b" width="24%" style="margin: 0 0.5%;"/>
  <img src="https://github.com/user-attachments/assets/e25df7e8-9657-4f91-bfc3-01e9f56fc80b" width="24%" style="margin: 0 0.5%;"/>
  <br>
  <em>(좌측부터) Full-Metal 무한궤도, 고강성 알루미늄 프레임, 고성능 DC 인코더 모터, KC 인증 보호회로 내장 배터리</em>
</div>

---

## ⚙️ 2. 시스템 및 하드웨어 구성

<details open>
<summary><b>🛠️ 로봇 구조 및 시스템 아키텍처 (클릭하여 열기/닫기)</b></summary>
<br>

<div align="center">
  <img src="https://github.com/user-attachments/assets/4d2a4687-b286-409f-8d9a-cfd09f1d15f9" width="48%" style="margin-right: 2%"/>
  <img src="https://github.com/user-attachments/assets/4bdb806e-b0ec-41ee-9303-f415333584ca" width="48%"/>
</div>
<br>
</details>

<br>

<details>
<summary><b>🧠 핵심 보드 및 주변 장치</b></summary>
<br>

* **AI 보드**: NVIDIA Jetson Orin Nano Developer Kit
* **지능형 제어보드**: MCU 기반 모터 및 센서 통합 제어
* **주변 장치**: AI 카메라, 고성능 DC 모터, 대용량 배터리

<div align="center">
  <img src="https://github.com/user-attachments/assets/ccfc5671-44c9-47bf-8762-30e06ead3247" width="31%" style="margin: 0 1%"/>
  <img src="https://github.com/user-attachments/assets/5329c21f-cfef-4249-ad0f-13fd010cc4c9" width="31%" style="margin: 0 1%"/>
  <img src="https://github.com/user-attachments/assets/ea7cf142-f69c-463e-9827-9b8168c842d2" width="31%" style="margin: 0 1%"/>
</div>
<br>
</details>

---

## 📋 3. 기술 사양 (Specifications)

| Category | Item | Description |
| :--- | :--- | :--- |
| **🏗️ Physical** | Weight | 약 2.5 kg |
| | Structure | 트랙형(탱크형) 자율주행 로봇, Full-Metal 고강성 알루미늄 프레임 |
| **🧠 AI Board** | **Model** | **NVIDIA Jetson Orin Nano Developer Kit** |
| | GPU | 1024 CUDA Cores + 32 Tensor Cores (Orin) |
| | CPU | 6-Core ARM Cortex-A78AE (64-bit) |
| **👁️ Vision** | Camera | AI 전용 카메라 모듈 |
| | 기능 | 객체 인식 / 자율주행 / 실시간 영상 처리 / 장애물 회피 |
| **🔌 Connectivity** | Interface | USB / UART / GPIO |
| | Communication | **ROS2 기반 표준 통신 아키텍처** |
| **🔋 Power** | Power Source | 리튬이온 배터리 기반, KC 인증 및 보호회로 내장 |
| **🧩 Expandability** | 확장성 | 다양한 센서 확장 / IoT 연동 / AI 모델 추가 가능 |

---

## 🎓 4. 교육 및 활용 (Curriculum & Mission)

### 📚 교육과정 및 패키지
<div align="center">
  <img src="https://github.com/user-attachments/assets/d530472c-f7b4-4b25-926a-4705df93b829" width="49%" style="margin-right: 1%"/>
  <img src="https://github.com/user-attachments/assets/2bb69bee-2d57-4252-bd93-5e45130998b2" width="49%"/>
</div>

### 🏁 개발 내용 및 대회 미션 프로세스
<div align="center">
  <img src="https://github.com/user-attachments/assets/4c8d70df-1097-4580-864a-58a9b0a18bb4" width="49%" style="margin-right: 1%"/>
  <img src="https://github.com/user-attachments/assets/cb4f5c25-f250-4a01-a19e-bd83e80f8a5e" width="49%"/>
</div>

---

<div align="center">
  <br>
  <img src="https://github.com/user-attachments/assets/7b6ed3f1-724c-4687-bb4f-078e967031ff" alt="경기장 이미지" width="100%" />
  <br>
  <em>실전과 같은 환경에서 테스트 가능한 경기장 시나리오</em>
</div>

<br>

---
<div align="center">
  <sub>Copyright © 2026 <b>AxisFab by Leekoos</b>. All rights reserved.</sub>
</div>
