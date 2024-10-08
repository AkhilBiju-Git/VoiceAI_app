# VoiceAI_app

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

_**<--This is the Intro of my APP**_

"Voice Assistant App with ChatGPT & Dall-E "is an exciting app that combines the power of AI to make your chats more interesting. You can chat, create images, and even have responses read to you. Plus, your chat history is safe, and we've got you covered if you forget your password. We've implemented a secure Firestore database and seamlessly integrated two powerful APIs - OpenAI for text and DALL-E for image generation. And the best part? We've crafted this app using Flutter, making it a seamless and user-friendly experience. It's your new way to chat and get creative with AI!
<br>

_**<--Navigatable pages**_
<br>
The application is composed of four distinct pages: the Authentication Page, Home Page, Chat Page, and Settings Page. Additionally, the app offers both dark and light themes for user customization.
<br>

1)Login/Signup Page<br>
![1](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/728b4c1b-9a70-4445-a3df-8d5663ad4a4c)
![2](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/6fda818d-8ac9-4e60-ae32-bea4e88b9502)<br>
![3](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/4f616818-af1c-4ffd-9ff0-b005c54a438c)
![4](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/6c39d91a-730e-4b71-ad94-22b363d595f0)
<br>
2)HomePage<br>
![5](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/381c8e20-18fa-4b36-a5d9-e4afe76ac31c)<br>
![6](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/423d40a0-f9d4-4323-82fd-8153566a00cf)
<br>

3)Settings Page<br>
![7](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/b89851e9-783d-49ba-b4a4-bcb45a7ddcd6)<br>
![8](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/6446c4b7-cfec-412f-949e-57bd18f49c7e)
<br>

4)Chat Page<br>
![12](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/ddbf2fbd-8ea2-410c-9f68-853581f43231)
![9](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/5071f071-0037-4cb5-852f-5af31089ba18)<br>
![11](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/d7261bb6-5552-4575-a191-e87884b8890e)
![10](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/0e1614d7-cef1-44e0-b3e2-328c8ab742d5)
<br>
_**<--API call Implementation**_
<br>
1)Firebase APIs:<br>
a)FirebaseAuth: This API is used for authentication and user management within your application.<br>
b)Cloud Firestore: This API is utilized for storing and managing your application's data in a NoSQL database hosted on Firebase.<br>
2)OpenAI APIs:<br>
a)ChatGPT-3.5-Turbo: This API, powered by OpenAI's GPT-3.5 Turbo, is integrated into your application for generating human-like text responses. It enables interactive and dynamic conversation capabilities.<br>
b)Dall-E: This API, likely referring to OpenAI's DALL-E, is used for generating images from textual descriptions. Please note that you've mentioned the API key for these services is stored in Firebase for secure access.<br>
<br>
This project utilizes Firebase APIs for authentication and data management, and OpenAI APIs, including ChatGPT-3.5-Turbo for text-based interactions and DALL-E for generating images from textual descriptions. The API keys for these services are securely stored in Firebase.


_**<--Design Inspiration Link**_

https://www.figma.com/file/DbgctMxCEyCCziMWhV0O3X/Gpt?type=design&node-id=0%3A1&mode=design&t=0ZJJMuQpJ8nKaUmm-1

_**<--Process to how to run the Project**_

1) Clone the project into any directory using the following command  -https://github.com/PapaBiju/VoiceGpt_app.git
2) Open terminal in the directory which you've cloned and type the following command - "flutter pub get".
3) Install flutter in your system before running the project and install the necessary plugins flutter and dart.
4) Recommended editor - VSCode
5) Now, select a device and run the project using the command - flutter run.
6) The app will run seamlessly on your selected device.
7) To use the voice features of the application, you need to run the app on the physical device instead of the emulator. 
8) Ensure you have good internet connection while running the APP.
To directly download the application into your mobile, go to this drive link and download the apk file - https://drive.google.com/drive/folders/188rqgQhvXdOVNdOaRwA4JMl9f_pjpZ3G?usp=sharing ""

You may get a prompt like this - "This document might contain unsafe content. Make sure you trust the sender before you open it". 
Please ignore this prompt and click on Open/Accept. Now after opening the file give the app all the required permissions, and then start using the app.
<br>While downloading the apk file you may get a prompt like this - "This document might contain unsafe content. Make sure you trust the sender before you open it". 
Please ignore this prompt and click on Open/Accept. Now after opening the file give the app all the required permissions, and then start using the app

_**<--Implementation**_

https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/cd012e32-f9c3-4337-865f-671c8bd85362


_**<--File structure**_

![image](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/72523d57-6d1d-4458-a7c0-242118d96f46)


_**<--Database Implementation / Data structure used**_

Firebase Authentication is responsible for managing user authentication and handling within the system.
The application utilises Firebase as its designated database platform, where all queries and responses are stored. Additionally, the images generated are temporarily stored by OpenAI.
<br>
DataStructure used by Firestore is List<Map<String,String> as given in below screenshots
<br>
Firebase Authentication (3 Emails were used for testing):
<br>
![1](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/a639a866-c792-46e8-bf2e-44fd56b32610)
<br>
Cloud Firestore:<br>
apiKey:
<br>
![2](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/e7bcf3f8-61fe-4053-8f0f-bf2b25c502cb)
<br>
History:
![3](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/1bd5bf6e-d535-437d-aec7-c61353bb031f)
Queries:
![4](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/3299e6c7-59d6-4efc-9acc-57162f3f91c5)

Usernames:

![5](https://github.com/PapaBiju/VoiceGpt_app/assets/112795188/0436e255-edc4-4b0a-982c-8c2ebe1c9ef9)


<br>

_**THANKYOU**_

