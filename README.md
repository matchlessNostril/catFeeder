![header](https://capsule-render.vercel.app/api?type=soft&color=698dd1&height=150&section=header&text=MulMeokNyang&fontSize=50&fontColor=FFFFFF&animation=fadeIn)

## 💻 Introduction

Our app is designed to manage the hydration of cats kept at home. The app connects to a smart water dispenser device equipped with AI that distinguishes each cat. Through the built-in camera of the dispenser, it updates the daily hydration of each cat in real-time. Users can view today's hydration, evaluations, and previous hydration statistics in the app. Additionally, it offers a co-management feature, allowing family members to collectively oversee the cats.

When creating a management space in the app, upon registering cat information, we collect five pictures of the cat to be used by an AI model. These images are processed through an AI model for breed recognition and extraction of characteristic colors. The resulting data is stored in the database. Using the camera integrated into the water dispenser, the real-time AI analysis of the cat currently drinking water is compared with the breed and color values stored in the database to recognize the individual cat. Subsequently, the hydration amount is updated in the database. However, as the actual connection to the water dispenser is not available, the verification of hydration updates cannot be performed.

![image](https://github.com/matchlessNostril/catFeeder/assets/81696717/1cae15de-b911-4d18-bd37-1af89ad017de)

## 📹 Demonstration Video
<a href="https://youtu.be/w5-AoBGKgJU?si=pbF0UQpNJNiQSJvY"> <img width="800" alt="thumbnail" src="https://github.com/matchlessNostril/catFeeder/assets/144131324/774b75fc-e567-4128-bcbb-a3ca1e102379"> </a>


## 🙇 Team members (Hanyang Univ)

|Name|Part|Dept|Contact|
|---|---|---|---|
|ChanSol Choi|Frontend|Information Systems|hjk9216@hanyang.ac.kr|
|YunSun Lee|Backend|Film and Theatre|justina7182@gmail.com|
|Jukyung Ahn|Backend|Information Systems|hyoju8618@naver.com|
|JunGgi Hong|AI|Information Systems|sentorino@hanyang.ac.kr|


## 🕐 Development Period
- `23.10-23.11`


## 📚 Tech Stack
<div>
	<b>FrontEnd </b>
	<img src="https://img.shields.io/badge/React Native-61DAFB?style=flat&logo=React&logoColor=white" />
	<img src="https://img.shields.io/badge/StyleSheet-DB7093?style=flat&logo=styled-components&logoColor=white" />
	<img src="https://img.shields.io/badge/Expo-000020?style=flat&logo=Expo&logoColor=white" />
</div>
<div>
	<b>BackEnd </b>
	<img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=Node.js&logoColor=white" />
	<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=MySQL&logoColor=white" />
  	<img src="https://img.shields.io/badge/AWS Lambda-FF9900?style=flat&logo=awslambda&logoColor=white" />
	<img src="https://img.shields.io/badge/AWS RDS-569A31?style=flat&logo=amazonrds&logoColor=white" />
	<img src="https://img.shields.io/badge/AWS S3-527FFF?style=flat&logo=amazons3&logoColor=white" />
</div>
<div>
	<b>AI </b>
	<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=OpenCV&logoColor=white" />
	<img src="https://img.shields.io/badge/Flask-000000?style=flat&logo=Flask&logoColor=white" />
  	<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=PyTorch&logoColor=white" />
	<img src="https://img.shields.io/badge/scikit learn-F7931E?style=flat&logo=scikitlearn&logoColor=white" />
</div>

## 📑 Document & AI Blog
- [Document](https://github.com/matchlessNostril/MulMeokNyang/blob/main/Documentation/NyangPort_Documentation.pdf)

- [Backend API Docs](https://www.notion.so/sorukun/MulMeokNyang-API-fef2fa29b47e4c978d3d57f32a4b1056)

- [AI Blog](https://bit.ly/3tfp9yn)


## ✔️ Available Device
- `Mobile (iOS/Android)`

## 📌 Application Features


### 1️⃣ Start

<img src="https://github.com/matchlessNostril/catFeeder/assets/77608505/4e534fdc-3faa-4ba5-b64a-d3a9c1db6975" alt="1_Start (1)" width="200"/>

- Click the "Sign up" button to proceed with the registration via email.


### 2️⃣ SignUp

<img src="https://github.com/matchlessNostril/catFeeder/assets/77608505/c94fb203-614e-4649-a1dd-d920c5a87bc0" alt="2_SignUp" width="600"/>

- Enter information in the email, password, and password confirmation fields.
- If the email and password are valid, proceed to the next screen.
- Verify your identity through message authentication.
- Enter the 6-digit authentication code and press the complete button to finish SignUp.


### 3️⃣ Login / Find Email / Find Password

<img src="https://github.com/matchlessNostril/catFeeder/assets/144131324/727ba433-407f-4a3a-8608-bc580c180f85" alt="3_Login" width="200"/>

- Log in with the email and password.
- The automatic login setting is only available for users who have completed user profile registration.
Users who have not yet registered their profile will receive an alert to set up automatic login after registration.


<img src="https://github.com/matchlessNostril/catFeeder/assets/144131324/7b208925-5c7b-4aa7-bf9f-2a7f845366da" alt="4_FindEmail" width="400"/>

- If you have forgotten your email, please click on the "Find Email" button.
By entering only your name and phone number, you can find your email.


<img src="https://github.com/matchlessNostril/catFeeder/assets/144131324/c6651916-cc4f-42b3-9f02-9fae60d20b1d" alt="5_FindPw" width="400"/>

- If you have forgotten your password, click on the "Forgot Password" button to proceed with SMS verification. After that, your password will be sent to the corresponding email.


### 4️⃣ User Profile Registration

<img src="https://github.com/matchlessNostril/catFeeder/assets/144131324/393b68f0-910a-4766-b240-e968a076c87a" alt="6_UserProfile" width="200"/>

- Enter a profile picture (optional), nickname, and self-introduction (optional).


### 5️⃣ Go To Management Space

<img src="https://github.com/matchlessNostril/catFeeder/assets/144131324/74ab85a0-d30f-4b60-ba8b-9520659d27d9" alt="7_CreateSpace" width="600"/>

- If you want to create a space to manage your pet cats,
Press the 'Create your own management space' button,
Proceed with the water supply registration to work with the management space.
- If you want to be a co-manager in an existing space, click 'Wait for co-manager registration'.
- Once additional co-manager registration is confirmed, it'll be navigated to the main screen immediately.


### 6️⃣ Cat Profile Registration

<img src="https://github.com/matchlessNostril/catFeeder/assets/144131324/8ef7cdf1-ed7d-4da3-b8d8-28df3245bcff" alt="9_CatProfile" width="200"/>

- Enter the profile picture of the cat, name, age, and weight.
  
<img src="https://github.com/matchlessNostril/catFeeder/assets/144131324/0c21adf0-0aa0-42b0-9cac-1eeded89b1f1" alt="10_AI" width="400"/>

- In order for the water dispenser to recognize the cat and record the daily hydration, users should conduct an AI analysis with five photos to classify the breed and extract the characteristic colors.
- The characteristic color will appear slightly darker considering the shadow according to the position of the water dispenser camera.

<img src="https://github.com/matchlessNostril/catFeeder/assets/144131324/4acb1163-2b50-441b-a180-d3907993d2a3" alt="11_CatFeed" width="200"/>

- Enter the wet food consumption information.
- It will be used as a calculation for the amount of recommended hydration.

<img src="https://github.com/matchlessNostril/catFeeder/assets/144131324/63203aa2-017e-45fc-90ca-84b4f1fe4cfa" alt="12_CatHydration" width="200"/>

- Set the daily goal hydaration.
- If you want to register a new cat, click the additional registration button. Or If you want to go straight to the management space, click the complete complete registration.


### 7️⃣ Main
<img src="https://github.com/matchlessNostril/catFeeder/assets/144131324/924973b4-fe64-4168-9645-c16abefc4235" alt="13_Main" width="400"/>

- Select a cat profile at the top to see the main information.
- You can see the daily goal hydration guage, with an evaluation message corresponding to the value.
- If you press the Statistics button, it'll be navigated to the period-based hydration statistics screen for the currently selected cat.


### 8️⃣ Hydration Statistics
<img src="https://github.com/matchlessNostril/catFeeder/assets/77608505/6decf4fd-1e79-49c2-9af5-cff86f6dc633" alt="14_StatisticsGraph" width="600"/>

<img src="https://github.com/matchlessNostril/catFeeder/assets/77608505/ba3b9b83-9917-4e9e-9ca2-e32d9047c763" alt="15_StatisticsCalendar" width="600"/>

- You can check the weekly, monthly, and yearly statistical graphs,
You can specify a specific period by clicking the calendar icon.
- Press the bar on the graph to see the exact figures.
- Select a cat profile at the top, You can see another cat's hydration statistic.


### 9️⃣ Drawer
<img src="https://github.com/matchlessNostril/catFeeder/assets/77608505/86bfba72-cec7-4967-982e-6d6988f12f8e" alt="16_Drawer" width="200"/>

- If you press the menu icon on the top right, the drawer will bring up from the right side.
The features of the drawer are following below.
- Modify user profile
- Add, modify, or delete cat profile
(To modify or delete, the cat selection alert will appear)
- Co-manager
- Log out


### 🔟 Co-manager
<img src="https://github.com/matchlessNostril/catFeeder/assets/77608505/09f23afd-1830-4ce7-a1e4-49772ccdc0da" alt="17_CoManager" width="400"/>

- You can see a list of other users who have been added as co-manager of the current space.
- If you are the representative manager, you can click the add co-manager button to add a new manager,
or you can also delete an existing manager by clicking delete icon.
