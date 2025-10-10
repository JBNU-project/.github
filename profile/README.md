![001](https://github.com/user-attachments/assets/faf4b195-809b-4c3a-893e-3da3f6bd6c9d)

# 🤖 Machina OCR: 다국어 웹툰 생성을 위한 AI 데이터셋 구축 및 아미지/텍스트 인식 
```
📚 다국어 웹툰 AI 데이터셋 구축 및 이미지/텍스트 인식 프로젝트
📆 2024.09.02 ~ 2024.12.20
🖥️ 전북대학교 캡스톤 디자인 프로젝트
```
---

## 🌟 프로젝트 소개

본 프로젝트는 웹툰의 다국어 번역을 위한 혁신적인 AI 솔루션 개발을 목표로 합니다. 이미지 처리, OCR, 기계 번역 기술을 결합하여 웹툰의 텍스트와 효과음을 자동으로 인식하고 번역하는 통합 시스템을 구축합니다.

## 프로젝트 활동 내역

<div align="center">
  <a href="https://github.com/JBNU-project/main/"><img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fkfpd.org&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%2370FF00&title=Machina+OCR+Main+Repository&edge_flat=false"/></a>
</div>

## 🛡️ 기술 스택

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![GPT-4](https://img.shields.io/badge/GPT--4-412991?style=for-the-badge&logo=openai&logoColor=white)
![Paddle](https://img.shields.io/badge/Paddle-2B50FF?style=for-the-badge&logo=paddlepaddle&logoColor=white)

## 👥 팀 구성

### 👥 Machina Sapience Team
| 강경태 | [PM]홍건하 | 최홍석 | 오준호 |
| :---: | :---: | :---: | :---: |
| <img width="160px" src= "https://github.com/user-attachments/assets/fa5865d1-5e6e-4738-bb95-eaff0b5b2892"/> | <img width="160px" src= "https://github.com/user-attachments/assets/8c156d05-acee-4d11-8ff3-4659e4a99dd8"/> | <img width="160px" src="https://github.com/user-attachments/assets/c98e0197-3648-4420-9c9e-2e5477fb0f09"/> | <img width="160px" src="https://github.com/user-attachments/assets/4daf0370-bbc7-4109-bd10-0feafe8c5aca"/> |
| [@gyeongtaekang](https://github.com/gyeongtaekang) | [@honggunha](https://github.com/honggunha) | [@ChatHongPT](https://github.com/ChatHongPT) | [@JH218](https://github.com/JH218) | 



## 🚀 주요 기술

- **Grounding DINO**: 이미지 객체 탐지
- **Paddle OCR**: 광학 문자 인식
- **GPT-4**: 텍스트 번역 및 처리
- **IOPaint**: 이미지 인페인팅
- **Naver Clova OCR**: 고성능 문자 인식

## 📅 프로젝트 타임라인

### 데이터 준비 단계
- **9월 2일 - 9월 15일**: 프로젝트 초기 기획 및 역할 분담
- **9월 16일 - 9월 30일**: 선행 연구 및 기술 조사
- **10월 1일 - 10월 15일**: 서비스 파이프라인 설계 및 데이터 준비

### 모델 개발 단계
- **10월 16일 - 10월 31일**: Grounding DINO 모델 테스트
- **11월 1일 - 11월 15일**: OCR 학습 및 성능 개선
- **11월 16일 - 11월 27일**: AI 번역 및 이미지 처리 기술 구현

### 최종 검증 및 문서화
- **11월 28일 - 11월 30일**: 모델 성능 분석
- **12월 1일 - 12월 2일**: 시연 자료 준비
- **12월 2일 - 12월 20일**: 최종 결과 보고서 작성

## 🎯 프로젝트 목표

1. 고성능 다국어 웹툰 번역 AI 데이터셋 구축
2. 이미지 내 텍스트 및 효과음 자동 인식 기술 개발
3. 기계 학습 기반 다국어 번역 시스템 구현

## 🦖 Grounding DINO 학습 과정

### Step 1: PSD 파일을 이미지로 변환 및 컷 추출
![Screenshot from 2024-12-18 16-16-41](https://github.com/user-attachments/assets/4a7b962b-8000-47e5-be0d-dcd46903350e)

### Step 2: 이미지 내 효과음 라벨링
![Screenshot from 2024-12-18 16-17-14](https://github.com/user-attachments/assets/ac669998-b679-4c99-9f88-434b88b4bd17)

### Step 3: 학습 데이터 생성
![Screenshot from 2024-12-18 16-17-52](https://github.com/user-attachments/assets/bd9ed585-32be-4599-90ba-6dc1566a4835)

### Step 4: Grounding DINO 학습
![Screenshot from 2024-12-18 16-18-56](https://github.com/user-attachments/assets/3a72b1c9-f523-4ad4-ba55-d5618b7ae3cd)

## 📷 Paddle OCR 학습 과정

### Step 1: PSD 파일 내 효과음 레이어 찾기
![Screenshot from 2024-12-18 16-28-21](https://github.com/user-attachments/assets/f53b87c8-fad2-4e9e-a3ac-6956e5a5167d)

### Step 2: 레이어 정보 추출 및 정제
![Screenshot from 2024-12-18 16-28-38](https://github.com/user-attachments/assets/ed9387a4-e1b7-41f0-886b-c9de17b0fdb0)

### Step 3: 학습 데이터 생성
![Screenshot from 2024-12-18 16-28-55](https://github.com/user-attachments/assets/af1459eb-e35c-4657-bca7-59f2e19947b3)

### Step 4: Paddle OCR
![Screenshot from 2024-12-18 16-29-12](https://github.com/user-attachments/assets/4a982a86-d27b-4e55-96af-10617d6744ee)

## 🔊 효과음 및 대사 제거 과정

### Step 1: 이미지 파일 내 효과음 탐지 및 좌표 가져오기
![Screenshot from 2024-12-18 16-29-43](https://github.com/user-attachments/assets/c974d87e-6887-49cf-9633-990ba82dbb2f)

### Step2: 효과음 좌표를 활용한 mask 파일 생성
![Screenshot from 2024-12-18 16-30-55](https://github.com/user-attachments/assets/a4d69a5e-2693-4336-94ae-9bcc9cd57ebd)

### Step3: PSD 파일 내 효과음 레이어 찾기
![Screenshot from 2024-12-18 16-31-11](https://github.com/user-attachments/assets/f9837dae-372f-4e24-9055-a110a9e94813)

### Step4: 결과
![Screenshot from 2024-12-18 16-31-33](https://github.com/user-attachments/assets/83a7c2ac-92be-4eeb-8aa5-2cf1a2567b9b)

## 📊 주요 기술적 성과

- 효과음 자동 추출 프로그램 개발
- 다중 OCR 모델 성능 비교 분석
- 이미지 인페인팅을 통한 텍스트 제거 기술 구현

## 🔧 서비스 파이프라인
![IMG_0400](https://github.com/user-attachments/assets/5d6b578f-cc28-466f-a6cc-9e0160b390fe)

## 📊 WBS (Work Breakdown Structure)
<img width="948" alt="스크린샷 2024-12-19 오후 2 45 58" src="https://github.com/user-attachments/assets/a0d68c92-436d-49a6-9c50-d8a69c4ea63d" />

## 🔗 관련 기술

![RoboFlow](https://img.shields.io/badge/RoboFlow-0080FF?style=for-the-badge&logo=roboflow&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![IOPaint](https://img.shields.io/badge/IOPaint-FF6B6B?style=for-the-badge&logo=medibangpaint&logoColor=white)
![GroundingDINO](https://img.shields.io/badge/GroundingDINO-70FFAF?style=for-the-badge&logo=Deno&logoColor=white)
![Naver Clova OCR](https://img.shields.io/badge/Naver_Clova_OCR-00C300?style=for-the-badge&logo=naver&logoColor=white)
![PaddleOCR](https://img.shields.io/badge/PaddleOCR-2B50FF?style=for-the-badge&logo=paddlepaddle&logoColor=white)

## 🔎 OCR 정확도 성능 비교
![KakaoTalk_20241218_163313363](https://github.com/user-attachments/assets/01df25c1-0282-4af1-894c-6af8187958a8)

- **Machina OCR**은 다른 OCR 시스템과 비교했을 때 뛰어난 성능을 자랑합니다. **Fine-tuned Paddle OCR** 기반으로 한 Machina OCR은 특정 데이터셋과 사용 사례에 맞게 최적화되었으며, 이로 인해 다른 업계 표준 OCR 시스템들을 크게 능가하는 성과를 거두었습니다.

## 주요 성과

### 1. **가장 높은 정확도**
- Machina OCR은 **88%** 의 정확도로, 다양한 OCR 시스템 중에서 **높은 정확도**를 기록했습니다. 이는 파인튜닝된 **Paddle OCR**의 뛰어난 성능을 바탕으로 달성되었습니다.

### 2. **기존 OCR 시스템들과의 비교**
- **Google OCR (42%)**, **Tesseract OCR (29%)** 등과 비교했을 때, Machina OCR은 **월등한 인식 성능**을 보이며, 다른 OCR 솔루션들을 압도했습니다.

### 3. **맞춤형 최적화**
- **지도 학습**과 **파인튜닝**을 통해 Machina OCR은 기존의 오프더쉘프 OCR 모델들을 특정 데이터셋에 맞게 최적화하였으며, 이를 통해 OCR 인식 정확도가 크게 향상되었습니다. 이 과정에서 **맞춤형 최적화**가 얼마나 중요한지를 잘 보여주고 있습니다.

### 4. **업계 선두 제품 능가**
- 파인튜닝된 **Paddle OCR**을 활용한 Machina OCR은 기존의 업계 선두 OCR 솔루션들에 비해 확연히 뛰어난 성과를 보이며, **OCR 기술의 발전 가능성**을 입증했습니다.
  

## 📊 성능 비교 차트

| OCR 시스템            | 정확도 (%) |
|--------------------|-----------|
| **Fine-tuned Paddle OCR (Machina OCR)** | **88%**     |
| **Naver Clova OCR**    | 58%       |
| **Google OCR**         | 42%       |
| **Tesseract OCR**      | 29%       |
| **Easy OCR**           | 21%       |

---

## 🎬 시연 영상

https://github.com/user-attachments/assets/66b7e280-f7ea-4c29-a7c4-c3d511b0ee22


