# Student Management System Created Using Django
This is a Simple Student Management System Developed While Learning Django.
Feel free to make changes based on your requirements.

## Features of this Project

### A. Admin Users Can
1. See Overall Summary Charts of Students Performances, Staff Performances, Courses, Subjects, Leave, etc.
2. Manage Staff (Add, Update and Delete)
3. Manage Students (Add, Update and Delete)
4. Manage Course (Add, Update and Delete)
5. Manage Subjects (Add, Update and Delete)
6. Manage Sessions (Add, Update and Delete)
7. View Student Attendance
8. Review and Reply Student/Staff Feedback
9. Review (Approve/Reject) Student/Staff Leave

### B. Staff/Teachers Can
1. See the Overall Summary Charts related to their students, their subjects, leave status, etc.
2. Take/Update Students Attendance
3. Add/Update Result
4. Apply for Leave
5. Send Feedback to HOD

### C. Students Can
1. See the Overall Summary Charts related to their attendance, their subjects, leave status, etc.
2. View Attendance
3. View Result
4. Apply for Leave
5. Send Feedback to HOD


## 📸 ScreenShots
<table>
    <tr>
        <td><img width="1366" height="622" alt="Capture1" src="https://github.com/user-attachments/assets/9a88ad8b-9d2b-4191-90c9-13475157d9d3" /></td> 
        <td><img width="1366" height="614" alt="studen" src="https://github.com/user-attachments/assets/cefa99ef-00bf-4ea9-9c40-4d8f854004d7" /></td> 
        <td><img width="1366" height="617" alt="Staff" src="https://github.com/user-attachments/assets/b3a64e41-2e7c-4e64-9aca-c8686fc72faa" /></td> 
    </tr>
</tabble>






## How to Install and Run this project?

### Installation
**1. Create a Folder where you want to save the project**

**02.Downloads and install python 3.10**

**03.Install virtualenv In Python**
```
pip instll virtualenv
```
**04. Clone this project**
```
git clone https://github.com/Kalharapasan/Group-07.git
```
**05.Then, Enter the project**
```
cd Group-07
```

**06.Cretae databases In you MySql Lacal Server and chnge configeration on seting.py in application** 
```
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'DATABASES_NAME',
        'USER': 'USER_NAME',
        'PASSWORD': 'USER_PASSWORD',
        'HOST': 'HOST',
        'PORT': 'PORT',
    }
} 
```

**07.Create a Virtual Environment and Activate**

**I.Install Virtual Environment First**
```
-->pip install virtualenv
```

**II.Create Virtual Environment**

For Windows 
```
--> python -m venv venv
```
For Mac
```
python3 -m venv venv
```
For Linux
```
--> virtualenv .
```

**III.Activate Virtual Environment**

For Windows
```
--> venv/scripts/activate
```

For Mac
```
--> venv/bin/activate
```

For Linux
```
--> bin/activate
```

**08. Install Requirements from 'requirements.txt'**
```
--> pip3 install -r requirements.txt
```

**09. Add the hosts**

- Got to settings.py file 
- Then, On allowed hosts, Use **[]** as your host. 
```
ALLOWED_HOSTS = []
```
*Do not use the fault allowed settings in this repo. It has security risk!*


**10. Now Run Server**

Command for PC:
```
-->python manage.py runserver
```

Command for Mac:
```
-->python3 manage.py runserver
```

Command for Linux:
```
-->python3 manage.py runserver
```

**11.Database Update**
```
-->python manage.py makemigrations
-->python manage.py migrate
```

**12. Login Credentials**

Create Super User (HOD)
Command for PC:
```
-->python manage.py createsuperuser
```
Then Add Email and Password

**or Use Default Credentials**

*For HOD /SuperAdmin*
Email: admin@admin.com
Password: admin

Command for Mac:
```
-->python3 manage.py createsuperuser
```
Then Add Email and Password

**or Use Default Credentials**

*For HOD /SuperAdmin*
Email: admin@admin.com
Password: admin

Command for Linux:
```
-->python3 manage.py createsuperuser
```
Then Add Email and Password

**or Use Default Credentials**

*For HOD /SuperAdmin*
Email: admin@admin.com
Password: admin


## Project's Journey
- [x] Admin/Staff/Student Login
- [x] Add and Edit Course
- [x] Add and Edit Staff
- [x] Add and Edit Student
- [x] Add and Edit Subject
- [x] Upload Staff's Picture
- [x] Upload Student's Picture
- [x] Sidebar Active Status
- [x] Named URLs
- [x] Model Forms for adding  student
- [x] Model Forms for all
- [x] Views Permission (MiddleWareMixin)
- [x] Attendance and Update Attendance
- [x] Password Reset Via Email
- [x] Apply For Leave
- [x] Students Can Check Attendance
- [x] Check Email Availability
- [x] Reply to Leave Applications
- [x] Reply to Feedback
- [x] Admin View Attendance
- [x] Password Change for Admin, Staff and Students using *set_password()*
- [x] Admin Profile Edit
- [x] Staff Profile Edit
- [x] Student Profile Edit
- [x] Student Dashboard Fixed
- [x] Passing Page Title From View  - Improved
- [x] Staff Dashboard Fixed
- [x] Admin Dashboard Fixed
- [x] Firebase Web Push Notifications
- [x] Staff Add Student's Result
- [x] Staff Edit Result Using CBVs (Class Based Views)
- [x] Google CAPTCHA
- [x] Student View Result
- [x] Change all links to be dynamic
- [x] Code Restructure - Very Important




