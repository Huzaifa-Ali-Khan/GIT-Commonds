Git Commands and Instructions
Project Setup and File Management
1. Open a Command Prompt in the project folder where you only want to push specific files and make copies to other folders.
2. Clear Global User Credentials:
  cmdkey /delete:git:https://github.com
3. Clear Local User Credentials:
   git config --unset user.name
   git config --unset user.email
4. Check User Configuration:
   - For local user:
     git config --list
   - For global user:
     git config --global --list

5. Sign-In with User Credentials:
   - For Huzaifa:
     git config user.name "Huzaifa-Ali-Szabist-ID"
     git config user.email "bscs2112352@szabist.pk"
   - For Uzair:
     git config user.name "Uzair-Memon-Szabist-ID"
     git config user.email “bscs2112350@szabist.pk”

- For Huzaifa-Ali:
git config user.email "huzaifalikhan48@gmail.com"
git config user.name "Huzaifa-Ali-Khan"
User Accounts
1. Uzair Account:
   - Email: bscs2112350@szabist.pk
   - Password: szabist.123


To follow before every push or pull
cmdkey /delete:git:https://github.com
git config --list
git config --unset user.name
 git config --unset user.email
git status


Creating and Pushing Code
Steps to Create a Repository and Push Code:
1. Initialize Git:
   git init
2. Check Status:
   git status
3. Add All Files:
   git add -A
4. Check Status Again:
   git status
5. Commit Changes:
   git commit -m "Relevant Comment"
6. Add Remote Repository:
   git remote add origin <repository-url>
7. Push to Remote Repository:
   git push -u origin master



### Creating a Branch:
1.   git branch <BranchName>
2.   git checkout <BranchName>

-Push Code in branches: -
git branch checkout dev
•	Pushing code in Branch
git add -A
git status
git commit -m “Comments”
git push origin <BranchName>
   		git push  (For another time)


•	Merging Dev branch
Git checkout master
Git merge dev
Git push origin master

•	After Working in Dev:- 
	Git add -A
	Git commit -m “Comments”
	Git push origin dev

•	Clone Repo
o	Git clone <url>
•	Pull Repo: -
o	Git pull origin dev

•	To fetch all branches: -
	Git pull
•	To fetch all branches: -
	Git fetch





