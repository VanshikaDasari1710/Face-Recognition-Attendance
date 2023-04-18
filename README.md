Face Recognition Attandance System
Recognize The faces And Take Automatic Attandance. ✨
Face Recognition Logo

GitHub

Motivation 😲
We seek to provide a valuable attendance service for both teachers and students. Reduce manual process errors by provide automated and a reliable attendance system uses face recognition technology.

Features 📋
Check Camera
Capture Faces
Train Faces
Recognize Faces & Attendance
Automatic Email
Screenshots 📷
Command Line Interface
Command Line Interdace

Checking Camera
Checking Camera

Automail
Automail

Tech Used 💻
Build With -

Python 3.7
Module Used -

All The Module are Latest Version.

OpenCV Contrib 4.0.1
Pillow
Numpy
Pandas
Shutil
CSV
yagmail
Face Recognition Algorithms -

Haar Cascade
LBPH (Local Binary Pattern Histogram)
Software Used -

Pycharm 2019.2
VS CODE
Git
Installation 🔑
Download or Clone the project
First Download or Clone the Project on Your Local Machine.To download the project from github press Download Zip

Download Zip

or

You can clone the project with git bash.To clone the project using git bash first open the git bash and write the following code

git clone https:https://github.com/VanshikaDasari1710/Face-Recognition-Attendance.git

Git clone

After download, Open the project using or VSCODE. Then we have to create an python enviroment to run the program.

create enviroment
First open the terminal or command line in the IDE.Then write the following code.

python -m venv env
Then activate the enviroment using the code below for windows.

.\env\Scripts\activate
[ Notice: If your pc don't have virtual enviroment or pip install the follow this link. How to create Virtual Enviroment ]

Installing the packages
After creating the enviroment on your project let's install the necessary packages.

pip isntall demo

To install those package open the terminal or command line and paste the code from below

pip install opencv-contrib-python
pip install numpy
pip install pandas
pip install Pillow
pip install pytest-shutil
pip install python-csv
pip install yagmail
[ **Notice: During the package installization, sometime it shows some error, to avoid those error you can install those packages as admin. ]

Test Run 🚴
After creating the enviroment and installing the packages, open the IDE terminal/command line to run the program. Using the code below.

py main.py
Here is a demo to run the program. I'm Using the 

Test Run

How To Use? 📝
If you want to use it just follow the steps below.

First download or clone the project
Import the project to your favourit IDE
Create an python enviroment
Install all the packages
Change the mail information
Run the project using the command line or your IDE Run Button
Known Bugs 🐛
This project have some bugs.

Student Details: In student details folder the StudentDetails.csv file don't have ID & name column.This problem show when the program run first time and create the StudentDetails.csv file automatically. To soleve the problelm just open the file and add ID & Name Column in the file and save it.
Auto Attachment: This is not a problem actually. The problem is before sent auto mail we have to manually change the file name. I tried to automate the attachment but i faild.
