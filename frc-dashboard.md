---
layout: page
title: FRC Dashboard
exclude: true
---

#### **FRC Dashboard Setup**
* Install [Node.js LTS](https://nodejs.org/en/)
* Cd to dashboard directory and run
~~~
npm install
~~~

<br>

#### **Running FRC Dashboard**
* Open Windows Command Prompt
* Navigate to FRC Dashboard directory
* Run
~~~
npm start
~~~

<br>

#### **Configure FRC Dashboard to run when FRC Driver station is opened**
* Compile to windows Executable file
  * Open Windows Command Prompt
  * Navigate to FRC Dashboard directory
  * Run
~~~
npm run-script package-win
~~~
* Change driver station default dashboard location
  * Navigate to “C:\Users\Public\Public Documents\FRC” and open “FRC DS Data Storage” in notepad
  * Make DashboardCmdLine equal to
~~~
“”C:\\Users\\USERNAME\\PycharmProjects\\PROJECT_NAME\\dist\\FRCDashboard-win32-x64\\FRCDashboard.exe””
~~~
Replacing USERNAME with your username and PROJECT_NAME with the name of your dashboard project
  * Save the file
  
**Note:**
If you make changes to your FRC Dashboard project and need the executable to update and reflect those changes, you will need to delete the FRCDashboard-win32-x64 directory before you run the script to compile the executable again.
