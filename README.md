# ShcliessFach Locker Project

#### Created by:
* Dominique Huang (202000216)
* Stephen Theodorus (202000232)


### About Project
Hello everyone. This is a project of an automated locker system with the app that receives and notifies users upon package arrival.

### Requirements
* Python 3.10.0 (or other Python 3 builds)
* Arduino IDE 1.8.16
* sqlite3

### Dependencies 
* pip install kink
* pip install matplotlib
* pip install tkinter
* pip install pyserial
* pip install pathlib

### Tools and Materials
* Arduino uno board
* Bread Board 
* 4-8 Servo, or possibly more (Feel free to modify the amount of servos to your hearts content, for it only needs a few tweaks to the program)
* Jumper Cable
* Locker Box (You can custom build this.)

## ## How To Run This Project
* Run The Program/App With Fresh New Database Tables: python -m schliessfach -dbinit = 'True'

* Run The Program/App With The Previous Database Tables: python -m schliessfach -dbinit = 'False'

* Run The App With A Mock Database: python -m schliessfach -dbinit = 'Demo'

### P.S.
I'm sorry that I don't collect all the .png files into one folder because I was in a hurry back when I created this project, and I am a bit lazy to make changes to my code, so please forgive me.

## WARNING
Please note that this project uses SMTP for emailing users and administrators. Before you run this project, please go to 'observer.py', find the observer classes. You will find a method called 'update' for each observer class. In the variable 'emailer', input your own email and password as the argument in the 'Emailer' class parameter.
