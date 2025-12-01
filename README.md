# Back-End Software Developer

<!-- Typing animation -->
<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&pause=900&center=true&vCenter=true&width=780&lines=Versatile+Backend+Developer+(C%2FC%2B%2B+%26+Java);System-level+performance+to+stable+services;Embedded+Linux+BSP+%C2%B7+LLM+engines+%C2%B7+REST+APIs;Cross-platform+(Linux%2FmacOS%2FWindows)+with+CMake"
    alt="typing"
  />
</p>

## LLM Router Engine (C++20 · llama.cpp · DeepSeek GGUF)
<div align="center">
  <p>
    <a href="https://www.youtube.com/watch?v=4t7U04pCidk&t=37s">
      <img src="https://img.youtube.com/vi/4t7U04pCidk/3.jpg" alt="YouTube" width="600">
    </a>
  </p>
</div>

<img width="3841" height="2404" alt="mlengine1" src="https://github.com/user-attachments/assets/04cbac27-bd03-490b-a26f-50574d3b34f1" />  

<img width="3841" height="2404" alt="mlengine2" src="https://github.com/user-attachments/assets/2d15fb5c-e3a8-410c-92a6-bc12666f8a44" />  

---  

## 🧑‍💻 About Me

I am a **versatile backend developer** with practical experience in both **C/C++ system programming** and **Java-based server development**.  
My work ranges from building **low-level engines and performance-critical components** to delivering **stable and scalable backend services** for enterprise environments.  

I focus on:  
- **Reliability** – designing backend architectures that remain robust under real-world usage.  
- **Performance** – applying system-level optimization skills learned from C/C++ to backend services.  
- **Practicality** – ensuring solutions align with actual business needs and user workflows.  

My experience includes **embedded Linux BSP training** (Vision Edge Device Academy),  
as well as **cloud MSP projects, public SI systems, and in-house platform development** at MTData.  
This background allows me to connect **system-level programming discipline** with **modern backend service design**,  
bringing balanced skills for diverse development contexts.  

---

저는 **C/C++ 시스템 프로그래밍**부터 **Java 기반 서버 개발**까지 경험한 **범용적인 백엔드 개발자**입니다.  
낮은 수준의 엔진과 성능 중심 컴포넌트 개발에서부터, 기업 환경에서 안정적으로 동작하는 백엔드 서비스 구현까지 폭넓은 영역을 다루어왔습니다.  

제가 개발에서 중요하게 생각하는 가치는 다음과 같습니다:  
- **신뢰성** – 실제 운영 환경에서도 안정적으로 동작하는 백엔드 구조 설계  
- **성능 최적화** – C/C++에서 익힌 시스템 레벨 최적화 역량을 서비스 개발에도 접목  
- **실용성** – 실제 비즈니스 요구와 사용자 흐름에 맞는 솔루션 구현  

경력으로는 **임베디드 리눅스 BSP 교육 (한화 Vision Edge Device Academy)**,  
**클라우드 MSP 및 공공 SI 프로젝트, 사내 관리 플랫폼 개발 (MTData)** 등을 수행했습니다.  

이 경험을 통해 **시스템 수준의 프로그래밍 역량**과 **현업 백엔드 서비스 설계 능력**을 균형 있게 겸비하게 되었으며,  
다양한 개발 환경에서 실질적인 가치를 만들어내는 것을 목표로 하고 있습니다.  

---
## Projects
# llmrc
 LLM 기반 리소스/환경 설정 관리 도구 (configuration & runtime control) 실험용 프로젝트입니다.  
주로 로컬 또는 클라우드 환경에서 LLM 모델의 설정, 로딩, 실행 옵션을 관리하기 위한 간단한 유틸리티 모음입니다.

## 주요 목적

- LLM 모델 설정(configuration) 파일 관리  
- 런타임 옵션 설정 및 환경 변수 제어  
- 모델 로딩/실행 시점마다 유연한 설정 적용  
- 개인 연구 및 테스트 환경 최적화 도구로 사용

## 현재 상태

- 초기 개발 단계  
- 주요 기능: 설정 구조 설계, 기본 config 파일 템플릿 제공  
- 향후 기능: 모델 로딩 자동화, 설정 변경 반영, 다양한 포맷 지원 예정

  
# QT_Kernel_OS
 Qt/C++로 만든 간단한 **CLI 기반 운영체제 시뮬레이터**입니다.  
프로세스, 메모리, 파일 시스템 등의 개념을 콘솔 UI로 실험해보기 위한 개인 학습 프로젝트입니다.

## Features

- Qt 기반 CLI 화면 출력
- 가상 프로세스 / 메모리 / 간단한 명령어 셸 구현
- OS 구조와 커널 개념을 테스트하기 위한 토이 프로젝트

## Demo

- Live Demo: https://azabell1993.github.io/QT_Kernel_OS/files.html
  
# ml-engine
 C++과 LibTorch로 만든 **간단한 ML/LLM 추론 엔진 오케스트레이션 프로젝트**입니다.  
로컬에서 GGUF/ONNX/Torch 모델을 호출하고, HTTP API 형태로 노출하는 것을 목표로 하였습니다.

## Features

- C++ / LibTorch 기반 모델 로딩 및 추론
- Crow(또는 유사한 경량 웹 프레임워크)를 이용한 REST API 서버
- llama.cpp, GGUF 모델과 연동 실험 (CPU/GPU 환경 테스트용)
