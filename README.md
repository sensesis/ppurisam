<h1>단체 문자 서비스 PPURISAM</h1>

![header](https://capsule-render.vercel.app/api?type=waving&color=CDE4AD&height=320&text=PPURISAM&fontSize=80&desc=AI와%20음성인식을%20이용한%20문자%20전송&descSize=40&descAlignY=70&fontColor=F8F8F8&fontAlignY=40&animation=fadeIn)

<br>

## 📝 목차
- [프로젝트 소개](#프로젝트-소개)
- [주요 기능](#주요-기능)
- [시스템 아키텍처](#시스템-아키텍처)
- [기술 스택](#기술-스택)
- [ERD](#ERD)
- [API](#API)
- [개발 기간](#개발-기간)
- [팀 구성](#팀-구성)

<br>

## ✉️프로젝트 소개
- 본 프로젝트는 [**SW 프리캡스톤 디자인 교과목**]을 통해 [**다우기술**]과 연계하여 진행되었습니다.
- [**PPURISAM**] 프로젝트의 목표는 '**누구나 쉽게 이용할 수 있는 서비스**'입니다.
- 기본적인 웹서비스 기능 이외에도 사용자의 편리성이라는 관점에서 **음성인식**과 **AI를 이용한 이미지 생성**, **챗봇**을 추가로 구현하였습니다.

<br>

## ✨주요 기능
- 페이지는 문자 전송 / 주소록 / 발송조회 / 마이페이지 로 구성되어, 기본적인 문자 서비스를 제공하고 있습니다
- 문자 전송 시, 사용자는 작성하고 싶은 문자에 대해 간략하게 입력하여 AI를 통한 **문자 템플릿**과 관련된 **이미지**를 제공받습니다.
- 그리고 이러한 과정 중 **음성인식**을 통해 키보드 입력을 최소화하여, 사용자의 접근성을 높였습니다.
- 또한, **챗봇** 서비스를 통해 페이지 이동없이 간편하게 문자 전송 서비스를 제공하여, 사용자의 편의성을 더욱 개선하였습니다.

<br>

### [초기화면]
<이미지>
<br>

### [회원가입&로그인]
![KakaoTalk_Photo_2024-11-26-22-32-13 002 (online-video-cutter com)](https://github.com/user-attachments/assets/4e6e4035-e0ae-45ab-9183-a1f088299346)

<br>

### [홈 화면]
<이미지>
<br>

### [문자 보내기]
<이미지>
<br>

### [주소록]
<이미지>
<br>

### [발송조회]
<이미지>
<br>

### [마이페이지]
![KakaoTalk_Photo_2024-11-26-22-32-12 001 (online-video-cutter com)](https://github.com/user-attachments/assets/18ede28a-9627-438a-a240-377e747dd10e)

<br>

## ⚙️시스템 아키텍처
![image](https://github.com/user-attachments/assets/50cb8354-b514-4c78-b123-8aedff0eb135)


<br>

## 💻기술 스택

- Front-end

|                             React                              |                         Javascript                          |                             CSS                              |                             Vite                              |
|:--------------------------------------------------------------:|:-----------------------------------------------------------:|:------------------------------------------------------------:|:-------------------------------------------------------------:|
| ![My Skills](https://skillicons.dev/icons?i=react&theme=light) | ![My Skills](https://skillicons.dev/icons?i=js&theme=light) | ![My Skills](https://skillicons.dev/icons?i=css&theme=light) | ![My Skills](https://skillicons.dev/icons?i=vite&theme=light) |  
<br>

- Back-end

|                                                                    Springboot                                                                    |                             MySQL                              |                                                                       ELK                                                                        |                             Nginx                              |                                                                 Prometheus / Grafana                                                                  |
|:------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------:|:-----------------------------------------------------------------------------------------------------------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/58e04523-c570-4d5d-b37c-a286fa74f0e6" width="50" height="50" style="border-radius: 13px;" > | ![My Skills](https://skillicons.dev/icons?i=mysql&theme=light) | <img src="https://github.com/user-attachments/assets/368e20df-4a89-4a7d-9da1-126358f78180" width="50" height="50" style="border-radius: 13px;" > | ![My Skills](https://skillicons.dev/icons?i=nginx&theme=light) | ![My Skills](https://skillicons.dev/icons?i=prometheus&theme=light)&nbsp;&nbsp;&nbsp;![My Skills](https://skillicons.dev/icons?i=grafana&theme=light) |
<br>

- 서비스 배포 및 실행 환경

|                                                                     AWS Ec2                                                                      |                             Docker                              |
|:------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------:|
| <img src="https://github.com/user-attachments/assets/7c5ae4ed-14c1-4830-adc5-d6d49bc18663" width="50" height="50" style="border-radius: 13px;" > | ![My Skills](https://skillicons.dev/icons?i=docker&theme=light) |
<br>

- 버전 및 이슈관리

|                      Github, Github Issues                      |
|:---------------------------------------------------------------:|
| ![My Skills](https://skillicons.dev/icons?i=github&theme=light) |
<br>

- 협업 툴

|                             Discord                              |                             Notion                              |
|:----------------------------------------------------------------:|:---------------------------------------------------------------:|
| ![My Skills](https://skillicons.dev/icons?i=discord&theme=light) | ![My Skills](https://skillicons.dev/icons?i=notion&theme=light) |
<br>

- 디자인

|                             Figma                              |
|:--------------------------------------------------------------:|
| ![My Skills](https://skillicons.dev/icons?i=figma&theme=light) |
<br>

<br>

## 💾ERD
<img src="https://github.com/user-attachments/assets/db930415-1ebd-4161-86b2-5a218c2fd607">
<br>
<br>

## 🌐API
<img src="https://github.com/user-attachments/assets/b7f46df1-b48f-4069-9129-7230b10cff81">
<img src="https://github.com/user-attachments/assets/461211d8-3b34-4db8-882b-a11bd565ccba">
<br>
<br>

## 📊모니터링&로그관리
![image](https://github.com/user-attachments/assets/3c7ced6f-7536-4824-ab6d-8d1c782ae410)

![image](https://github.com/user-attachments/assets/82359acc-eafb-4734-ad27-3d82fe7d20f2)
<br>

## 📆개발 기간
- 2024-09-20 ~ 2024-11-??
  <br>

## 🤝팀 구성

|                                                                           **배건우**                                                                           |                                                                             **진기태**                                                                             |                                       **박진성**                                        |                                       **박지원**                                        |                                       **장원진**                                        |
|:-----------------------------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------:|:------------------------------------------------------------------------------------:|
|                                                         <center>팀장<br>Frontend<br>Backend</center>                                                          |                                                              <center>Frontend<br>Backend</center>                                                               |                               <center>Backend</center>                               |                               <center>Backend</center>                               |                              <center>Frontend</center>                               | 
| [<img src="https://github.com/user-attachments/assets/a75ab739-e053-4f9d-89f7-7bf33cecb115" height=150 width=150> <br/> @bkw535](https://github.com/bkw535) | [<img src="https://github.com/user-attachments/assets/b65e1842-38b8-4164-8319-12b5393e479a" height=150 width=150> <br/> @sensesis](https://github.com/sensesis) | [<img src="" height=150 width=150> <br/> @Jinseong01](https://github.com/Jinseong01) | [<img src="" height=150 width=150> <br/> @jiwonp7747](https://github.com/jiwonp7747) | [<img src="" height=150 width=150> <br/> @wonjinjang](https://github.com/wonjinjang) |
