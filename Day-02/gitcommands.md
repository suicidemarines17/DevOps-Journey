## Git Commands Cheat Sheet

This serves as a basic cheat sheet for basic git commands that will be used in VS terminal. Since I have not used the others, I will just list the ones I have used so far. 


| **`git init`** | Creates a hidden `.git` folder inside of the project directory 

* Turns a normal directory into a repository that tracks your changes

* Only needs to be ran onces at the start of a new project

| **`git status`** | Shows what files git is currently tracking or ignoring

* Displays the modified files in red and stagged files in green

* Acts as saftey check before saving

| **`git add .`** | Stages everthing you've done in the directory

* use the `.` to represent what directory to stage

* Speeds up workflow by saving everything all at once

| **`git commit -m "Add Message Here"`** | Saves your chances to the local git database.

* The **`-m`** represents sending a short message and you would just replace **`"Add Message Here"`** explaining what you did. Make sure to add the quotation marks

* Creates a unique ID number called a "Hash" for tracking

| **`git push`** | Uploads what you've done to the remote server

* Makes changes visible to the team 

* Will fail if someone uploads changes before you update your code

| **` git pull`** | Fetches the latest code from the server to your machine

* Automatically merges changes directly into your local files

* Keeps files synchonized with the team

