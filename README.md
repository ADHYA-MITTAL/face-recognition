# Attendance Tracking using face Recognition
### Table of contents <BR>
1. [About the project](https://github.com/ADHYA-MITTAL/face-recognition#about-the-project)<br>
    - [Requirements of the project](https://github.com/ADHYA-MITTAL/face-recognition#requirements-of-the-project)<br>
    - [Compatible platforms](https://github.com/ADHYA-MITTAL/face-recognition#compatible-platform)<br>  
2. [Agile Methodology](https://github.com/ADHYA-MITTAL/face-recognition/#agile-methodogoly)<br>
    - [How I used this methodology in my project](https://github.com/ADHYA-MITTAL/face-recognition#how-i-used-this-methodology-in-my-project)<br>
3. [Project Flow](https://github.com/ADHYA-MITTAL/face-recognition/#project-flow) <br>
4. [Resources Used](https://github.com/ADHYA-MITTAL/face-recognition/#resource-used)
  
## About The Project
- It is an Attendance tracking aaplication which recognize people by their faces, mark their attendance by recording their name and their entry time in an excel sheet.
- This project is made during microsoft engage 2022.<br>
### Requirements of the project
Mentioned in [requirement.txt](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/requirement.txt) .All these libraries must be preinstalled for the code to run properly. <br>
### Compatible Platform:<br>
Laptop,Desktops,Tablets
## Agile Methodogoly
Agile is an approach for software/project development and evolving solution through colloabration between self organising and cross functional team.
### How I used this methodology in my project
**Week 1(planning,research,design):**<br>
In this week ,i went through various github project and youtube videos to know about the different libraries used in this project. I searched for the tutorials and worked on UI design of the project.<br>
**Week 2:**<br>
 I continue working on the code and research what new i can incorporate in my project. Encountered bugs in the project which i tried to debug.<br>
**Week 3:**<br>
 completed the attendance tracking model which was recoganizing the face of different people whose images have been stored in back-end by accessing the video camera.Then it was marking the attendace of that person by recording their name and their entry time in an excel sheet named as [attendandance.csv](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/attendance.csv)<br>
## Project Flow
- For running the attendance tracking model, run [face.py]() and for running the webportal through which attendance can be marked run [app.py]()<br>
- After you run the project you have to register your face so that system can identify you, so click on register new student<br>
- After you click a small window will pop up in that you have to enter you ID and name and then upload your image.<br>
- Once you register, you can mark your attendance by clicking on the button mark your attendance and then webpage [app.py]().You can view the attendance after clicking View Attendance button. It will show record in tabular format.
## Resource Used
 [Face detection using webcam](https://realpython.com/face-detection-in-python-using-a-webcam/#pre-requisites)<br>
 [Flaskweb Framework](https://www.youtube.com/watch?v=Az1MH_e1hVA)<br>
 [face recognition using diiferent library](https://analyticsindiamag.com/a-complete-guide-on-building-a-face-attendance-system/)
