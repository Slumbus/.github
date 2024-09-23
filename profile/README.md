# 🌃 아이 맞춤형 자장가 AI 작사작곡 앱 슬럼버스(Slumbus)
<p align="center">
<img alt="image" src="https://github.com/user-attachments/assets/54163e78-a8a8-46a8-a3bf-c96bf414b4c6">
</p>

## 👶🏻 프로젝트 정보
### 슬럼버스(Slumbus)
>보호자와 아이 간 정서적 유대감을 강화하는 창의적 어플리케이션으로,
>
>**AI의 도움**을 받아 아이를 위한 특별한 **자장가를 작사, 작곡**하여
>
>아이와의 순간을 더욱 의미 있게 만듭니다.
<br />

### Introduction
- 덕성여자대학교 컴퓨터공학전공
- 2024 ICT멘토링 한이음 공모전 출품작
- 개발기간: 2024.02~2024.09
<br />

## 👤 팀 소개
|       오지연       |       박유정        |      양규리        |       유민경       |       이하늘       |                                                                                                               
| :-----------------: | :-----------------: | :----------------: | :----------------: | :----------------: |
| <img width="160px" src="https://github.com/user-attachments/assets/d6f56bcc-6aaa-495c-a071-81b47f184de5" /> | <img width="160px" src="https://github.com/user-attachments/assets/4aab592c-2142-4765-b47b-654e73f66491" /> | <img width="160px" src="https://github.com/user-attachments/assets/2c83526f-56d1-470b-b957-3f3e704bb2a8"/> | <img width="160px" src="https://github.com/user-attachments/assets/b06961df-d30b-4f28-a0c5-f0806240ff7d"/> | <img width="160px" src="https://github.com/user-attachments/assets/87e21dcb-b0f4-4dd8-b7b8-7e7b6aa227e1"/> |
| Full-stack | Full-stack | Full-stack | Full-stack | Full-stack |
| [@ninano05](https://github.com/ninano05) | [@qkrdbwjd](https://github.com/qkrdbwjd) | [@ygreee0320](https://github.com/ygreee0320) | [@mk020](https://github.com/mk020) | [@twosky0202](https://github.com/twosky0202) |
<br />

## 📃 프로젝트 소개
### 개발 배경 및 필요성
📉 출생률 감소
> 전 세계적으로 출생률이 감소하고 있는 가운데, 대한민국 2023년 4분기 합계 출생률은 0.65명 입니다. <br />
> 출생률의 감소는 아이를 키우는 보호자의 육아 관심을 높이고, <br />
> 자장가를 작사 및 작곡하는 앱은 보호자의 요구를 충족시키는 동시에, 아이의 성장과 발달에 도움을 줄 것입니다.

😴 자장가의 중요성
> 자장가는 아이를 재우거나 달래는 데 사용되는 중요한 도구로, 영유아의 심리적 안정과 편안한 수면을 돕습니다. <br />
> 매체를 통해 들려주는 자장가보다 보호자가 직접 불러주는 자장가가 영유아의 심리적 건강성에 의미 있는 영향을 미치며, <br />
> 아이와의 애착 안정성의 발달에 크게 이바지합니다.

🤝🏻 고유한 자장가 생성
> 세계에 존재하는 다양한 자장가는 모든 아이에게 적합하지 않을 수 있습니다.<br />
> 슬럼버스(Slumbus)를 통해 직접 작사, 작곡하여 사용자가 자신의 아이만을 위한 고유한 자장가를 만들 수 있습니다. <br />
> 사용자는 개성 있는 자장가를 만들어 아이에게 들려줄 수 있으며, <br />
> 아이는 자신의 부모가 직접 만든 자장가를 들으며 안정감을 느낄 수 있습니다.
<br />

### 기획 의도
- 허밍의 음악적 요소(높낮이, 속도, 리듬 등)에 따라 태아의 움직임 패턴 기록
- 데이터 기반 맞춤형 자장가 작곡, 태아~영아의 안정적 수면 제공
- 맞춤형 자장가 작사, 작곡하여 아이와의 순간을 더 의미 있게 만들며,보호자와 아이 간 정서적 유대감 강화
<br />

### 서비스 명
- 영어 슬럼버(_slumber: 깊은 잠_)와 라틴어 옴니버스(_Omnibus: 모든_)의 합성어로, **모든 이를 위한 깊은 잠** 의미
<br />

## :movie_camera: Preview
<img src="https://github.com/user-attachments/assets/e07f72db-5ba6-4cbd-acfa-8edb86edc7ac" />
<br />
<br />


## :bulb: Key Features
### 보호자의 허밍에서 주요 멜로디(Pitch) 추출
 > 사용자가 자장가의 기본 멜로디가 될 허밍 음성을 입력하면, 서버에서 SPICE 모델을 사용해 허밍에서 주요 음정(Pitch)을 추출합니다. <br />
 > 이 추출된 Pitch 데이터는 AI 작곡 모델에 전달되어 활용됩니다. <br />
### 생성형 AI MusicGen에 추출된 Pitch 데이터와 장르, 악기 프롬프트를 사용한 자장가 작곡
 > 사용자는 MusicGen 모델을 이용해 자장가를 작곡합니다. <br />
 > 멜로디 데이터는 사용자가 허밍한 소리에서 SPICE 모델을 통해 추출한 Pitch 데이터를 사용하고, 사용자가 선택한 분위기(mood)와 악기(instrument)를 모델로 전달합니다. <br />
 > 모델은 추출한 허밍 Pitch를 기본 멜로디로 하여 선택한 분위기(mood)와 악기(instrument)로 자장가를 작곡합니다. <br />
### ChatGPT 모델을 사용한 사용자 맞춤형 자장가 가사 작사
 > 사용자가 아이의 이름과 원하는 가사의 스타일을 입력하면, 이를 프롬프트로 전달합니다. <br />
 > ChatGPT 프롬프트 엔지니어링을 통해 자장가 가사의 길이와 형식을 지정하고, 사용자의 요청에 맞춰 가사를 생성합니다. <br />
### 자장가별 아이 반응 기록
 > 6가지 상태(깊은 수면, 얕은 수면, 기쁨, 불편, 울음, 화남)를 등록하고, 곡에 대한 반응 코멘트를 작성할 수 있습니다. <br />
 > 이를 통해 작사, 작곡한 여러 자장가 중 아이에게 가장 잘 맞는 자장가를 찾도록 합니다.
<br />


 ## :computer: Tech Stack
- Client: <img src="https://img.shields.io/badge/React_Native-%2320232a.svg?style=flat-square&logo=react&logoColor=%2361DAFB"/> <img src="https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=axios&logoColor=%2361DAFB"/>
- Server: <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
- AI-Server: <img src="https://img.shields.io/badge/Flask-%23000.svg?style=flat-square&logo=flask&logoColor=white"/>
- DB: <img src="https://img.shields.io/badge/MySQL-4479A1.svg?style=flat-square&logo=mysql&logoColor=white"/> <img src="https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white"/>
- Deploy: <img src="https://img.shields.io/badge/Amazon%20EC2-FF9900?style=flat-square&logo=Amazon%20EC2&logoColor=white">
- Storage: <img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=Amazon%20S3&logoColor=white">
<br />

## :file_folder: Menu Structure
<img src="https://github.com/user-attachments/assets/ddf8797f-7a46-4ded-a434-c617c5266b59" />
<br />
<br />

## 🎨 UI/UX 디자인 및 데이터 모델링
- Figma
<img alt="image" src="https://github.com/user-attachments/assets/20ffbf9a-4402-48fb-a489-d682ba31303c">

<br />
<br />

- ERDCloud
<img alt="image" src="https://github.com/user-attachments/assets/f75c2aa2-4c57-4bf5-b225-8f3182f7bce0">
<br />
<br />

## :hammer: System Architecture
<img src="https://github.com/user-attachments/assets/c31ea605-47a6-4f6f-8cdd-929afd5ac495" width=700 />
<br />
<br />









<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
