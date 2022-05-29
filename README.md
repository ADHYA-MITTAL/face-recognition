# Attendance Tracking using face Recognition
### Table of contents <BR>
1. [About the project](https://github.com/ADHYA-MITTAL/face-recognition#about-the-project)<br>
    - [Requirements of the project](https://github.com/ADHYA-MITTAL/face-recognition#requirements-of-the-project)<br>
    - [Compatible platforms](https://github.com/ADHYA-MITTAL/face-recognition#compatible-platform)<br>  
2. [Agile Methodology](https://github.com/ADHYA-MITTAL/face-recognition/#agile-methodogoly)<br>
    - [How I used this methodology in my project](https://github.com/ADHYA-MITTAL/face-recognition#how-i-used-this-methodology-in-my-project)<br>
3. [Project Flow](https://github.com/ADHYA-MITTAL/face-recognition/#project-flow) <br>
4. [Future Scope of my project](https://github.com/ADHYA-MITTAL/face-recognition#future-scope-of-my-project)<br>
5. [Resources Used](https://github.com/ADHYA-MITTAL/face-recognition/#resource-used)
  
## About The Project
- It is an Attendance tracking aaplication which recognize people by their faces, mark their attendance by recording their name and their entry time in an excel sheet.
- This project is made during microsoft engage 2022.<br>
### Requirements of the project
Mentioned in [requirement.txt](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/requirement.txt) .All these libraries must be preinstalled for the code to run properly. <br> All the html files are included in [template](https://github.com/ADHYA-MITTAL/face-recognition/tree/main/templates) folder.The home page of the website is [main.html](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/templates/main.html) , login page is [login.html](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/templates/login.html) and mark your attendance page is [index.html](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/templates/index.html)
### Compatible Platform:<br>
Laptop,Desktops,Tablets
## Agile Methodogoly
Agile is an approach for software/project development and evolving solution through colloabration between self organising and cross functional team.
### How I used this methodology in my project
 SCRUM is subset of Agile,an approach for developing software.The basic time working unit is the sprintand their planning is limited to sprints.
- **Sprint 1(May 5):planning,research,design**<br>
In this week ,i went through various github project and youtube videos to know about the different libraries used in this project. I searched for the tutorials and worked on UI design of the project.<br>
- **Sprint 2(May 13):**<br>
 I continue working on the code and research what new i can incorporate in my project. Encountered bugs in the project which i tried to debug.<br>
- **Sprint 3(May 23):**<br>
 Completed the attendance tracking model which was recoganizing the face of different people whose images have been stored in back-end by accessing the video camera.Then it was marking the attendace of that person by recording their name and their entry time in an excel sheet named as [attendandance.csv](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/attendance.csv).<br>I even worked on the front-end of my website and tried to use flask to incorporate python code of attendance tracking model with my website. 
## Project Flow
- For running the attendance tracking model, run [face.py](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/face.py) and for running the webpage which will access the camera for recording attendance, run [app.py](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/app.py).
- This is the website for attendance tracking where the user have three options- To register themselve , To mark their attendance and third option is to view the marked attendance
    ![image](https://user-images.githubusercontent.com/79329319/170869219-d317135c-ffe2-4c9f-bd16-c19edf2e47f4.png)

- After clicking on the first icon,the user have to register themselve if they are new users by entering their enrollment number and then uploading their image. Screenshot of the website is shown below:<br>
    ![image](https://user-images.githubusercontent.com/79329319/170869487-ec2c6c45-6b3f-4e0a-9996-d82606ce80e5.png)
- Once registered, they can mark their attendance.They have to click on secon icon where they will be directed to a page which will access the camera and mark the attendance.or For this we can run the file [app.py](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/app.py) Camera will automatically recoganize their face if their data is stored and will mark their attendance by recording their name and entry time.One can view the attendance which will be shown in [attendance.csv](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/attendance.csv).
- Screenshot of Attendance Tracking<br>
    ![image](https://user-images.githubusercontent.com/79329319/170871101-26268822-0456-4166-939b-9526c5fc1603.png)
- Attendance sheet<br>
    ![image](https://user-images.githubusercontent.com/79329319/170871144-21c0bb49-2cc1-47b7-8bdb-c2d88a0a6f12.png)
## Future Scope of my project:<br>
- This can be used by university/colleges/school/organizations to mark the attendance of their employee/students.
- Sheet or webpage can be attached to the view your attendance option of  [main.html](https://github.com/ADHYA-MITTAL/face-recognition/blob/main/templates/main.html) to view the attendance record.
- using the backenend to store the data entered in the registeration page.
    
## Resource Used
 [Face detection using webcam](https://realpython.com/face-detection-in-python-using-a-webcam/#pre-requisites)<br>
 [Flaskweb Framework](https://www.youtube.com/watch?v=Az1MH_e1hVA)<br>
 [face recognition using diiferent library](https://analyticsindiamag.com/a-complete-guide-on-building-a-face-attendance-system/)
