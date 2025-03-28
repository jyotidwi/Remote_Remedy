 # <p align="center">💖RemoteRemedy</p>
<!-------------------------------------------------------------------------------------------------------------------------------------->
 <div align="center">
 <p>

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
 </p>
 </div>

<!-- --------------------------------------------------------------------------------------------------------------------------------------------------------- -->

<div id="top"></div>

<h2>🧾 Table of Contents</h2>

 [📌 Introduction](#introduction).<br>
 [💡 Features](#features).<br>
 [🚀 Technology Used](#technology-used).<br>
 [⭐ Overview](#overview).<br>
 [💥 Getting Started](#getting-started).<br>
 [🐳 Docker Setup](#docker-setup).<br>
 [⚡ Project Admin & Mentors](#project-admin-and-mentors).<br>
 [📑 License](#license).<br>
<br>

<!-- --------------------------------------------------------------------------------------------------------------------------------------------------------- -->

<h2>📌Introduction</h2>

RemoteRemedy is designed to make healthcare simple and accessible for both doctors and patients. It allows patients to connect with doctors through video calls, manage their health records, and make payments easily. For doctors, the app provides tools to schedule consultations, write prescriptions, and manage their time effectively.

<h2>💡Features</h2>

🚨 For Patients:<br>
 - Book Video Calls: Easily schedule video consultations with doctors.
 - Share Feedback: Rate and review the doctor after your consultation.
 - Manage Your Profile: Update and view your personal details.
 - View Past Records: Check previous orders and prescriptions in one place.
 - Easy Payments: Use the wallet feature powered by Stripe for secure payments.
 
🚨 For Doctors:<br>
 - Set Up Your Profile: Add information about yourself and your services.
 - Manage Availability: Set your working hours for consultations.
 - Join Video Calls: Connect with patients at the scheduled time.
 - Write Prescriptions: Share prescriptions directly with patients after the consultation.
 - Queue System: Organize appointments efficiently with a smart queue feature.

<!-- --------------------------------------------------------------------------------------------------------------------------------------------------------- -->

<h2>🚀Technology Used</h2>

<p>
  <a href="https://www.w3schools.com/html/"> <img src="https://img.icons8.com/?size=64&id=20909&format=png" alt="HTML" /></a>
  <a href="https://www.w3schools.com/css/"> <img src="https://img.icons8.com/?size=64&id=21278&format=png" alt="CSS" /></a>
  <a href="https://www.w3schools.com/js/"> <img src="https://img.icons8.com/?size=64&id=108784&format=png" alt="JS" /></a>
  <a href="https://www.w3schools.com/REACT/DEFAULT.ASP"> <img src="https://img.icons8.com/?size=64&id=NfbyHexzVEDk&format=png" alt="React" /></a>
  <a href="https://www.w3schools.com/sass/"> <img src="https://img.icons8.com/?size=64&id=qsQZWvMuX4ad&format=png" alt="SCSS" /></a>
  <a href="https://www.w3schools.com/python/"> <img src="https://img.icons8.com/?size=64&id=13441&format=png" alt="Python" /></a>
  <a href="https://www.geeksforgeeks.org/flask-tutorial/"><img src="https://img.icons8.com/?size=64&id=ewGOClUtmFX4&format=png" alt="Flask" /></a>
  <a href="https://www.w3schools.com/mongodb/"> <img src="https://img.icons8.com/?size=64&id=74402&format=png" alt="Mongo" /></a>
  <a href="https://www.educative.io/blog/docker-compose-tutorial" ><img src="https://img.icons8.com/?size=64&id=22813&format=png&color=000000" alt="Docker"></a>
</p>

🚨 Frontend: ReactJs <br>
🚨 Styling: TailwindCSS <br>
🚨 Backend: Python, Flask <br>
🚨 Database: MongoDB Atlas<br>
🚨 Containerization: Docker <br>
<!-- --------------------------------------------------------------------------------------------------------------------------------------------------------- -->

<h2>⭐Overview</h2>

<h1 align="center"> <a href="https://jyotidwi-remoteremedy.vercel.app/"> Live Project Demo ↗️</a></h1>

![](https://github.com/jyotidwi/Remote_Remedy/blob/master/Overview/1.png)
![](https://github.com/jyotidwi/Remote_Remedy/blob/master/Overview/2.png)
![](https://github.com/jyotidwi/Remote_Remedy/blob/master/Overview/3.png)
![](https://github.com/jyotidwi/Remote_Remedy/blob/master/Overview/4.png)
![](https://github.com/jyotidwi/Remote_Remedy/blob/master/Overview/5.png)
![](https://github.com/jyotidwi/Remote_Remedy/blob/master/Overview/6.png)


<h3 align="right"><a href="#top">⬆️</a></h3>

<!-- --------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>💥Getting Started</h2>

- Fork this Repository.
- Clone the forked repository in your local system.
  
 ```bash
 git clone https://github.com/<your-github-username>/Remote_Remedy.git
 ```
<h2>💻Local Setup</h2>

- Navigate to the project directory for frontend Setup.
  
 ```bash
 # Navigate to frontend directory
 cd frontend    
 # Install all npm packages for react frontend
 # Use `npm ci` to avoid changing package-lock.json after every install https://stackoverflow.com/a/56254478  
 npm ci
 # Set .env file
 copy .env.example .env
 # (For linux) cp .env.example .env
 # Start the frontend 
 npm run dev    
 ```

- Navigate to the project directory for backend Setup.
  
 ```bash
 # Navigate to backend directory
 cd backend
 # Set .env file
 copy .env.example .env
 # (For linux) cp .env.example .env
 # Create a virtual environment
 python -m venv venv # This will create a folder named venv inside your project directory
 # Activate the virtual environment
 venv\Scripts\activate
 # Install all dependencies for flask server
 pip install -r requirements.txt     
 # Run flask server
 flask run
 # deactivate the virtual environment, when you are done
 deactivate
 ```
- Navigate to the project directory for ML model Setup.
  
 ```bash
 # Navigate to backend directory
 cd models
 # Create a virtual environment
 python -m venv venv # This will create a folder named venv inside your project directory
 # Activate the virtual environment
 venv\Scripts\activate
 # Install all dependencies for flask server
 pip install -r requirements.txt     
 # Run flask server
 flask run
 #update the development server link in .env file of frontend(MODEL_URL)
 # deactivate the virtual environment, when you are done
 deactivate
 ```
<!-- --------------------------------------------------------------------------------------------------------------------------------------------------------- -->

## How to Get `.env` File Variables

Refer to the [EnvVarSetUpGuideline.md](.github/EnvVarSetUpGuideline.md) for detailed steps on setting up the `.env` files for both the frontend and backend.


<h3 align="right"><a href="#top">⬆️</a></h3>

<!-- --------------------------------------------------------------------------------------------------------------------------------------------------------- -->
<h2>🐳Docker Setup</h2>

Docker provides an easier way to set up and run RemoteRemedy with all its dependencies.

### Prerequisites
- Docker and Docker Compose [installed](https://www.docker.com/products/docker-desktop/) on your system
- Environment variables ready for configuration

### Steps to Run with Docker

1. Clone the repository same as above:

2. Update Enviroment variables:
   - Update Environment variables mentioned in docker-compose based on each project's `.env` respectively


3. Start the application using Docker Compose:
```bash
docker-compose up --build -d
```

The application will be available at:
- Frontend: http://localhost:3000
- Backend: http://localhost:5000

### Stopping the Application
```bash
docker-compose down
```

### Remove the Container
```bash
docker-compose kill
```

<h3 align="right"><a href="#top">⬆️</a></h3>

<!-- --------------------------------------------------------------------------------------------------------------------------------------------------------- -->

<h2>⚡Project Admin and Mentors</h2>

<table>
<tr>
<td align="center">
<a href="https://github.com/keshavpal22"><img src="https://avatars.githubusercontent.com/u/106235495?v=4" height="140px" width="140px" alt="Keshav Pal"></a><br><sub><b>Project Admin - Keshav Pal</b></sub>
</td>
<td align="center">
<a href="https://github.com/garvit0906"><img src="https://avatars.githubusercontent.com/u/151006036?v=4 height="140px" width="140px" alt="Garvit Varshney"></a><br><sub><b>Team Member - Garvit Varshney</b></sub>
</td>
<td align="center">
<a href="https://github.com/aryapriyanka11"><img src="https://avatars.githubusercontent.com/u/109778541?v=4" height="140px" width="140px" alt="Priyanka Arya"></a><br><sub><b>Team Member - Priyanka Arya</b></sub>
</td>
<td align="center">
<a href="https://github.com/jyotidwi"><img src="https://avatars.githubusercontent.com/u/128375571?v=4" height="140px" width="140px" alt="Jyoti Dwivedi"></a><br><sub><b> Team Member - Jyotsnanand Dwivedi</b></sub>
</td>

</tr>
</table>

<!-- ---------------------------------------------------------------------------------------------------------------------------------------------------------   -->
<h2>🧾License</h2>

This project is licensed under the Apache License 2.0. See the [LICENSE](https://github.com/jyotidwi/Remote_Remedy/blob/master/LICENSE) file for more details.
  
  ```
   Copyright 2025 TeamRemedy

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
  ```

