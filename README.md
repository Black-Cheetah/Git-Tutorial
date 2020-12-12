# Git-Tutorial
_My First Repository For Learning Git &amp; GitHub_ :octocat:
<br /><br />
![Git Logo](images/git-logo.png)

## Notes :
* Git Is Distributed Version Cotrol System
* Git Is Free And Open Source
* GitHub Is A Source For Projects &amp; Sources, Like [ GitLap, BitBucket ]
* GitHub Simplify Using Git
* You Can Use Git Without GitHub
* Git Has GUI

## Why To Learn Git :
* Developers Contribute To The Same Project
* You Can Revert Changes
* You Can Collaborate To Fix Issues
* You Can Solve Conflicts
* You Can Organize Features

## Words To Know :
* Repository -> Repo For Short
* Branch -> A Copy Of Repo
* Local Repo
* Remote Repo
* Commit [ Snapshot Or Checkpoint In Your Local Repo ]
* Clone [ From Local Or Remote ]
* Push [ Upload Local Changes To Remote Repository ]
* Pull [ Pull Changes From Remote Repo To Your Local One ]
* Pull Request [ Tell Others About Your Changes To Pull Them From Local Remote ]

## Important Notes :
* Create Repository For Every Project
* Create A New Branch For Every Feature Or Enhancement
* You Don't Have To Connect To Remote Repo While You're Working Offline
* Push &amp; Pull Depend On Permissions

## Git Commands :
* Clone Repository
	1. Open a terminal and change to a directory to place the project in
	2. Input : ```git clone Repository_Address```
- Show Status :
	- ```git status``` [ To Know What's Happening ]
* Add &amp; Remove Files To Staging Area [ Stage / Unstage ] :
	1. Add Specific Files : ```git add File_1 File_2,... Directery_1 Directory_2,...```
	2. Add All Files : ```git add *```
	3. Undo Add : ```git reset head File_Name``` [ Unstage ]
* Commit Changes To Local Repository :
	- ```git commit -m "Description For The Changes You've Done"``` [-m Stand For Message]
* Push Files To Remote Repository :
	1. Show Branches Names : ```git branch```
	2. Show Remote Name And Link : ```git remote -v```
	3. Push Files : ```push Remote_Repo_Name Local_Branch_Repo_Name```
* Pull Files From Remote Repository :
	- ```git pull Remote_Repo_Name```
* Pull & Push At The Same Time :
	-```push -u Remote_Repo_Name Local_Branch_Repo_Name```

### Generate An SSH Key And Use It To Connect With GitHub :
1. Generate A Key With Command Line [ ```ssh-keygen -t rsa -b 4096 -C email@example.sth``` ]
2. Copy The Key From The File And Add It To The Repository In GitHub
3. Test The Key [ ```ssh -T git@github.com``` ]

### Create A Repository From An Existing Project :
1. Go To The Folder With The Terminal And Write [ ```git init``` ] For Initialize
2. Add And Commit Your Project Locally
3. Create A Repository In GitHub And Copy The Link [ You Can Use HTTPS Or SSH ]
4. Go Back To The Command Line And Write [ ```git remote add Remote_Repo <The Copied Link>``` ]
5. Then Push The Project [ ```git push -u Remote_Repo Local_Repo``` ]
