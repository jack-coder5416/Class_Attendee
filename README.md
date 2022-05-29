# Microsoft Engage Mentorship program'22 project

## Class Attendee - Automated attendance marking tool for whole class in just one click by faculty using Face Recognition
###  <img src="https://user-images.githubusercontent.com/79541495/170813925-32c9d52c-b292-427d-91d0-dc2196901e47.png" width="20" height="20"> Overview 
As it's difficult or very time consuming to take attendance of students on papers also sometimes students mark the fake proxy of their friends :grin: So to remove this I came with a solution: Class Attendee !!

**Class Attendee** - An automated attendance marking tool that uses **facial recognition** to take attendance of the whole class to easen work and save time for the professor. This is solely built during the period of **Microsoft Engage Mentorship program'22** conducted by Microsoft to provide mentorship and to enrich freshmen with various software development techniques.

#### Problem statement (as given)
To build a fully functional prototype to demonstrate the application of Face Recognition Technology

##  <img src="https://user-images.githubusercontent.com/79541495/170813925-32c9d52c-b292-427d-91d0-dc2196901e47.png" width="20" height="20"> General Features and Interfaces:
Feature | Images
------------ | -------------
**SignUp Page**  
 It is fast, easy to use, and incredibly convenient with a minimalistic UI ! Firstly You need to signUp or make your profile as professor by entering the given fields | <img width="953" alt="image" src="https://user-images.githubusercontent.com/79541495/170838347-095226e9-6a85-4cee-af0e-3bbe247c3fd3.png">
**Login Page**  
 After creating the profile you will redirected to login page here you need to re-enter your credential  | <img width="949" alt="image" src="https://user-images.githubusercontent.com/79541495/170838380-5804555b-384a-4efa-b845-bf7c41dff5da.png">
**HomePage** 
After successfully login HomePage appears there will be four cards **Take Attendance , Add Student , Update Student Details , Search Attendance**|<img width="1000" alt="image" src="https://user-images.githubusercontent.com/79541495/170851723-a40fb603-b87e-4ffd-ac71-143f0852a253.png">
**Add Student** 
This is foremost thing to do , you need to add all students of class into it only one time they all record into the database. There is number of fields **First Name , Last Name , Registration ID , Branch , Year , Section and most required thing Profile Picture** |<img width="449" alt="image" src="https://user-images.githubusercontent.com/79541495/170815009-79ad688a-d771-4d3e-b2d0-473c1d79c560.png">
**Take Attendance** 
Professor need to enter the details about class like **Branch , Year , Section and Period**. There is also a feature that In a day the attendance of same period again is not allowed | <img width="423" alt="image" src="https://user-images.githubusercontent.com/79541495/170815034-686e884b-680d-4137-908a-8e3676e07f06.png">
**Update Student Details** 
Professor can update the details of registered students. Here professor need to enter the **Registration ID and branch**.|<img width="441" alt="image" src="https://user-images.githubusercontent.com/79541495/170815122-cce7cc72-8e63-4d1b-aa72-e4b09f7bd60e.png">
**Search Attendance**
Professor can search the marked attendance can also filter the attendance also | <img width="423" alt="image" src="https://user-images.githubusercontent.com/79541495/170815146-fb327b81-136f-4e24-a777-871027108dc8.png">
**Logout**
Professors can logout easily without any complexity just in a click and can also see his/her details|<img width="275" alt="image" src="https://user-images.githubusercontent.com/79541495/170839509-38ca79f2-7622-49cf-959f-ae60d3e3f865.png">



##  <img src="https://user-images.githubusercontent.com/79541495/170813925-32c9d52c-b292-427d-91d0-dc2196901e47.png" width="20" height="20"> Features of Attendance Taken Model:
Feature | Images
------------ | -------------
**Face Visibility** The Face appear on a window over there a green box mention your **Registration ID**. |<img width="916" alt="image" src="https://user-images.githubusercontent.com/79541495/170849612-749ab4a2-1453-4cfb-8786-1c686087ffd0.png">
**Multiple Face Recognition** As the foremost feature that we can record attendance of multiple students , we can also scan profile pictures on teams,meet meeting as well as in physical classes too | <img width="935" alt="image" src="https://user-images.githubusercontent.com/79541495/170849592-a488ebf3-60bd-4881-ab8d-632eff4ce601.png">
**Marking Attendance** To record the attendance first the system automatically scanned the faces and you as a professor need to **press S key** and then you will redirected to present period attendance detail.| <img width="955" alt="image" src="https://user-images.githubusercontent.com/79541495/170851777-cf34e7c5-ad28-4c90-8f94-953216e2232b.png">




## 🌐 Web flow
<img width="716" alt="image" src="https://user-images.githubusercontent.com/79541495/170849388-b6abafb6-4b74-493f-a462-745e949f60d0.png">

##  <img src="https://user-images.githubusercontent.com/79541495/170813925-32c9d52c-b292-427d-91d0-dc2196901e47.png" width="20" height="20"> Agile methology and workflow:
Agile methology was followed by implementation of sprint of 6 days in a week , continuous integration and development.

| Week | Task |  Remarks |
|------|:----:|---------|
| 1    | **Design & Setup phase** Basic app built by exploring technologies  , Setup Django server , Setting up the authentication system and database  |   Successfull setup implementation, authentication system|
| 2    | **Face Recognition Model** Building the face recognition custom model using using [Face_Recoginition Library](https://face-recognition.readthedocs.io/en/latest/readme.html) , Integration of Model , Testing Recognition Features |    All bugs resolved & Implemented Successfully            |
| 3    | **Build Phase** Integrating the face_recognition Library with backend , Adding Students to backend,Implementing Updation of student Profile(Bug), Advanced Search Functionalities, Framed the user with **Registration ID** |     Problem statement tasking completed|
| 4    | **Deployment and Design** UI Fixes, **Testing and review**  , Homepage , Manual Testing of every feature  |    Task completed     |

##  <img src="https://user-images.githubusercontent.com/79541495/170813925-32c9d52c-b292-427d-91d0-dc2196901e47.png" width="20" height="20"> Technologies used:
<img width="601" alt="image" src="https://user-images.githubusercontent.com/79541495/170850416-df14b298-ab73-49f4-9394-d27b4850e12c.png">

#### Programming Languages : <img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"/> <img alt="HTML5" src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"/> <img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"/><img alt="Bootstrap" src="https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white"/>
#### Version Control : <img alt="Git" src="https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/>  
####  Frameworks/Libraries : [Face_Recoginition Library](https://face-recognition.readthedocs.io/en/latest/readme.html) 


##  <img src="https://user-images.githubusercontent.com/79541495/170813925-32c9d52c-b292-427d-91d0-dc2196901e47.png" width="20" height="20">Installation/Environment Setup 

  #### 1. Clone App
  
  * Write the following command and press enter.
  
  ```
    $ git clone https://github.com/jack-coder5416/Class_Attendee.git
  ```
    
 #### 2. Install  Python and Django 
  * Install the latest version of Python with pip.
  * Install the latest Django framework.
  
  
 #### 3. Install  required libraries
  * Opened the cloned folder run following command on command prompt.
  * To run the web app on your local computer, install the required libraries(requirements.txt) using the command.
 
   ```
   pip3 install -r requirements.txt 
  ```
  
 #### 4. Run Locally
  * While you are still inside the cloned folder, write the following command in command prompt to run the website locally.
 
 ```
   python manage.py runserver
 ```
 
 
 ###### NOTE: This concurrently runs server and frontend, give a few seconds for frontend to load and the port by default will be ```http://127.0.0.1:8000/```
 
 
##  <img src="https://user-images.githubusercontent.com/79541495/170813925-32c9d52c-b292-427d-91d0-dc2196901e47.png" width="20" height="20"> Future Plans :-

Feature | Explanation
------------ | -------------
Export Attendance as Excel | User/Professor can easily fetch attendance in form of excel.
Security Features | The web-application would provide more security and better user interface and user experience to the product.
Class Management | All class management activities (branch/section wise) separately for every year students, creating assignment in the application itself assigning tasks and keep a record of every student activites individually in different sections.

Thank you ! Microsoft Team for such a wonderful mentorship program ❤️
You can also check [My weekly record during this program](https://docs.google.com/document/d/1PaFxscNCjT1GlZ6RX0_xjOat_sDtHPlQNbA5FWHMcjs/edit?usp=sharing)
