# Midterm-Part-3: Headset Construction

## Setting Up a Github Repo
In class, we went over this portion of the assignment, but just in case you missed it here is a quick recap. It is a requirement for this project for every team to have a github repository.

First, make sure everyone in your team has a Github account. One person on the team will need to "own" the repository, but don't worry, all of the contributions you make are tracked by the profile of who commits them, so it won't appear to be only that person's work. When creating the repository, before you hit the big green button to finalize creation, make sure you add a *.gitignore* file from the gitignore dropdown for Unity. After the repository is created, go into it's settings and add the rest of your team as collaborators.

Now that you have a repo created, using whatever tool you prefer ([Github Desktop Client](https://desktop.github.com/) *recommended*, [Git Kracken](https://www.gitkraken.com/), [Git Bash](https://git-scm.com/downloads)), clone the project in your desktop. Once you have cloned the project, create a new Unity project with Unity Hub in the cloned folder. From there, follow the instructions of your chosen tool to make your first commit and push the code to github.

## Importing the Qualisys Library
The manufacture of the motion capture system we will be using is [Qualisys](https://www.qualisys.com/). You can check out their website here. They also have a [Unity plugin](https://www.qualisys.com/software/unity/) that will make our lives easy. You can install [qualisys plugin](http://www.qualisys.com/download/Qualisys-Real-Time-Streaming.unitypackage) by downloading the package, then opening up your Unity project and in the top menu selecting **Assets->Import Package->Custom Package** and selecting the downloaded file. If you look in the Assets section of the project in Unity, you should now see a project folder.

## Connecting to the Tracking System
Get scripts
Attach connector to game manager
record your first object to test
attach qtm script to object

## Sensor Fusion
Camera Parent
QTM Object on parent
Do offset from accelerometer
realize this is bad
Add second object Transform proxy
Do diff
Apply lerp

## Drawing
Create empty and attach qtm object
Create stroke prefab
Add pen body and pen tip
Create new stroke and add points while button down

## Submitting
Submit a link to your github repo on canvas, and demonstrate to me the final product.

## Bonus
Neither of these are required for this assignment, just suggestions for if you want to take this further.
- Add another type of brush, maybe one that's flat, or a tube **Up to 4pts**
- Add a color selector, must support at least 5 colors **2 pts**
