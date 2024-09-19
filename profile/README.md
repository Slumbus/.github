# 슬럼버스

## 프로젝트 정보


## 팀


## 프로젝트 소개



## :movie_camera: Preview
<img src="https://github.com/user-attachments/assets/e07f72db-5ba6-4cbd-acfa-8edb86edc7ac" />
<br />
<br />


## :bulb: Key Features
1. 보호자의 허밍에서 주요 멜로디(Pitch) 추출
 > 사용자가 자장가의 기본 멜로디가 될 허밍 음성을 입력하면, 서버에서 SPICE 모델을 사용해 허밍에서 주요 음정(Pitch)을 추출합니다. <br />
 > 이 추출된 Pitch 데이터는 AI 작곡 모델에 전달되어 활용됩니다. <br />
2. 생성형 AI MusicGen에 추출된 Pitch 데이터와 장르, 악기 프롬프트를 사용한 자장가 작곡
 > 사용자는 MusicGen 모델을 이용해 자장가를 작곡합니다. <br />
 > 멜로디 데이터는 사용자가 허밍한 소리에서 SPICE 모델을 통해 추출한 Pitch 데이터를 사용하고, 사용자가 선택한 분위기(mood)와 악기(instrument)를 모델로 전달합니다. <br />
 > 모델은 추출한 허밍 Pitch를 기본 멜로디로 하여 선택한 분위기(mood)와 악기(instrument)로 자장가를 작곡합니다. <br />
3. ChatGPT 모델을 사용한 사용자 맞춤형 자장가 가사 작사
 > 사용자가 아이의 이름과 원하는 가사의 스타일을 입력하면, 이를 프롬프트로 전달합니다. <br />
 > ChatGPT 프롬프트 엔지니어링을 통해 자장가 가사의 길이와 형식을 지정하고, 사용자의 요청에 맞춰 가사를 생성합니다. <br />
4. 자장가별 아이 반응 기록
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
