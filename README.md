# phonegapappsF

UCL Location Based Quiz App

This app will provide with different multiple-choice questions related to UCL as an institution throughout UCLs main campus. In the different locations around the campus, depending on the location of the user certain questions will appear. As well as this, the addition of any questions to the app can be achieved by the use of a question setting browser app that is connected to a database. (see https://github.com/JorgeCerme/QUESTIONSETTING.git)

Getting Started

To run servers, open command terminal in BitVise SSH Client:

App-Server
cd /home/studentuser/code
cd phonegapappsF
sudo su
(insert Password)
cd zcesjce
Phonegap serve

Questions-Server
cd /home/studentuser/code
cd QUESTIONSETTING
node server.js

Prerequisites

To download the app for Android, https://build.phonegap.com/apps/3153604/download/android/?qr_key=eF2Zhj9RUgRGxHY2VkwG
To download the app for Windows Phone https://build.phonegap.com/apps/3153604/download/winphone/?qr_key=eF2Zhj9RUgRGxHY2VkwG
Web Browser: developer.cege.ucl.ac.uk:31291 

Deployment

Download apk file into user device, start servers, app will launch map and question specific positions automatically. Click button at the bottom of the app interface to obtain location data: latitude, longitude and marker in the map.

Walk around and see how you live a trace of your displacement. Try get close to the questions shown on the map and they will pop up with a multiple choice question. 

Built With

    Notepad++ - The script framework used
    Bitvise SSH Client - Dependency Management
    pgAdmin III PostgreSQL - Used to conect and generate table in database

(README.md template from: https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
