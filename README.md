# 📚 AI Storybook Maker App

> 본 앱은 **이경아님의 "그림동화책 만들기 앱"의 아이디어와 워크플로우를 참고하여 제작되었습니다.**
> (Inspired by and adapted from Lee Kyung-Ah's Storybook Creation App)

---

## 소개

AI를 활용하여 어린이 그림동화책을 쉽고 빠르게 제작할 수 있는 웹앱입니다.

사용자는 아이디어만 입력하면 다음 과정을 순서대로 진행할 수 있습니다.

1. 줄거리 생성
2. 캐릭터 설정
3. 페이지별 원고 생성
4. 삽화 프롬프트 생성
5. 영상 프롬프트 생성(선택)

ChatGPT, Claude, Gemini 등 생성형 AI와 함께 사용할 수 있도록 설계되었습니다.

---

## 주요 기능

### 1단계 : 줄거리 만들기

- 주인공 설정
- 대상 연령 선택
- 주제 입력
- AI용 줄거리 프롬프트 자동 생성
- 생성 결과 저장

---

### 2단계 : 캐릭터 만들기

- 주인공 캐릭터 설정
- 조연 캐릭터 생성
- 외형 및 성격 정의
- 캐릭터 일관성 유지용 설정 생성

---

### 3단계 : 페이지별 원고 생성

- 총 페이지 수 설정
- 페이지당 글자 수 설정
- 동화책 전체 원고 생성
- 페이지별 내용 분리

---

### 4단계 : 삽화 프롬프트 생성

- 페이지별 삽화 설명 생성
- Midjourney
- ChatGPT 이미지 생성
- Stable Diffusion
- Flux
- Ideogram

등 다양한 이미지 생성 AI에서 사용 가능

---

### 5단계 : 영상 프롬프트 생성 (선택)

- 이미지 애니메이션용 프롬프트 생성
- Runway
- Kling
- Hailuo
- Pika
- Luma

등의 영상 생성 AI에서 사용 가능

---

## 사용 방법

### Step 1

줄거리 생성

↓

### Step 2

캐릭터 생성

↓

### Step 3

페이지 원고 생성

↓

### Step 4

삽화 프롬프트 생성

↓

### Step 5 (선택)

영상 프롬프트 생성

↓

완성 🎉

---

## 사용 가능한 AI

### 텍스트 생성

- ChatGPT
- Claude
- Gemini

### 이미지 생성

- ChatGPT Image
- Midjourney
- Flux
- Stable Diffusion
- Ideogram

### 영상 생성

- Runway
- Kling
- Hailuo
- Pika
- Luma

---

## 기술 스택

- HTML5
- CSS3
- JavaScript (Vanilla JS)

별도의 서버 없이 브라우저에서 실행 가능합니다.

---

## 설치 방법

### GitHub 업로드

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/your-id/storybook-maker-app.git
git push -u origin main
