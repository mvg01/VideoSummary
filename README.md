<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&text=🧀%20VideoSummary%20-%20영상%20요약%20웹%20시스템&textColor=ffffff&fontSize=45&animation=twinkling&section=header" 
    width="100%" 
  />
</p>
<div align="center">
AI 기술을 활용하여 스토리 중심 또는 하이라이트 중심의 핵심 장면만을 추출해
<br>
<strong>고품질 요약 영상을 자동 생성</strong>하는 웹 기반 시스템입니다.
</div>

---

## 🎬 작품 개요

> **“긴 영상, 빠르게 핵심만 보고 싶다면?”**

현대 사회는 영상 콘텐츠 소비가 급증하고 있으며, 기업과 기관에서도 긴 영상을 짧게 요약하려는 수요가 커지고 있습니다.  
**VideoSummary**는 이러한 수요를 해결하기 위해 만들어진 **AI 기반 영상 요약 플랫폼**입니다.

사용자는 단순히 `.mp4` 영상 파일을 업로드하기만 하면,  
AI가 자동으로 **스토리 기반** 또는 **하이라이트 기반**으로 요약 영상을 생성하여 제공합니다.

- 요약 방식: `스토리 중심` ↔ `하이라이트 중심` 간 가중치 조절 가능  
- AI 모델: `PGL-SUM`, `Whisper`, `TransNetV2` 등을 활용한 다단계 분석
- 웹 기반 서비스로 **접근성과 활용도**를 극대화

---

## 🛠️ 시스템 구성

<img width="1326" height="683" alt="videosummary 구조도" src="https://github.com/user-attachments/assets/c83b00ec-3e3e-4d9b-91dd-de1c7b1ede79" />


### 🔧 개발 환경 및 도구
- **언어**: Python, JavaScript (Node.js)
- **개발 도구**: Visual Studio Code, Git
- **운영 환경**: Windows + Conda 가상환경

### 🤖 주요 AI 기술
- **프레임 중요도 점수화** (PGL-SUM 기반)
- **장면 전환 탐지** (TransNetV2)
- **중요도 기반 장면 선택 및 요약**
- **음성 단위 탐지 및 자막 생성** (Whisper)
- **자연스러운 요약 영상 병합** (음성 끊김 보정)

---

<div align="center">

## 📷 주요 화면

<br>
<img width="3670" height="2110" alt="videosummary 영상 요약 옵션" src="https://github.com/user-attachments/assets/2df059db-f98c-4777-92e8-d0b154388b1f" />
<br><sub>업로드 및 옵션 선택 화면</sub>
<br><br>

<img width="3670" height="2110" alt="videosummary 요약 진행" src="https://github.com/user-attachments/assets/b3e2bcd5-e987-40df-9b2e-66aaa9f9d044" />
<br><sub>요약 처리 과정</sub>
<br><br>

<img width="6630" height="3830" alt="videosummary 요약 결과" src="https://github.com/user-attachments/assets/d7ab5315-62e3-4231-8bef-4da6b778edd1" />
<br><sub>요약 결과 영상</sub>

</div>

---

## ▶️ 사용 방법

1. `.mp4` 영상을 업로드합니다.
2. 요약 성향을 슬라이더로 설정합니다.  
   - ⬅️ 스토리에 가까운 요약 ~ ➡️ 하이라이트에 가까운 요약  
3. 원하는 요약 영상 길이를 입력합니다. (선택)
4. **[요약 시작]** 버튼을 클릭합니다.
5. 생성된 요약 영상, 자막, 품질 점수를 확인하고 다운로드할 수 있습니다.


---

## 👩‍💻 팀원 및 역할

| 이름 | 담당 |
|------|------|
| **김은비** | AI 모듈 개발, 장면 중요도 점수 산정 |
| **윤단비** | AI 모듈 개발, 장면 선택 알고리즘 구현 |
| **전아린** | 음성 탐지 및 자막 생성, 웹 UI 제작 |
| **이동건** | 특징 추출, 장면 분할, 웹 서버 구축 |

> **지도교수:** 황기태 교수님

---

## 💡 기대 효과

- ✅ 스토리 중심 요약을 통한 영상 흐름 보존
- ✅ 하이라이트 중심 요약을 통한 흥미 유도
- ✅ 정부기관/기업용 보고 영상 자동 요약에 활용 가능
- ✅ 웹 기반으로 **장소, 기기 제약 없이 사용 가능**

---

## 📃 라이선스

Copyright (c) 2023  
All rights reserved.

This code is provided for **academic, non-commercial use only**. Redistribution and use in source and binary forms, with or without modification, are permitted for academic non-commercial use provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.  
2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation provided with the distribution.

This software is provided by the authors "as is" and any express or implied warranties, including, but not limited to, the implied warranties of merchantability and fitness for a particular purpose are disclaimed.  
In no event shall the authors be liable for any direct, indirect, incidental, special, exemplary, or consequential damages (including, but not limited to, procurement of substitute goods or services; loss of use, data, or profits; or business interruption) however caused and on any theory of liability, whether in contract, strict liability, or tort (including negligence or otherwise) arising in any way out of the use of this software, even if advised of the possibility of such damage.

---
