#This is a Readme File To know How to Clone and Push any code to Your Repo and how to push using access token
1. Install Git To Your PC
2. Open Git Bash
3. Clone Your existing Repository or Create a new Repository
4. Add some file to your local Repository.
5. command git status shows the file status of your local repo
6. command git add<filename> makes your file status to stagging
7. command git commit -m "Message" makes your file commit
8. git push origin master push your file to remote repository

==========================================================
Github Bash now a days don't support password authentication. Git now asks for access token for safe login.
You can create your access token from your github profile section follow the below steps:

1. Log into GitHub
2. Click on your name / Avatar in the upper right corner and select Settings
3. On the left, click Developer settings
4. Select Personal access tokens and click Generate new token
5. Give the token a description/name and select the scope of the token
    I selected repo only to facilitate pull, push, clone, and commit actions
    Click the link Red more about OAuth scopes for details about the permission sets
6. Click Generate token
7. Copy the token – this is your new password!
Now your password is your accesstoken. while push or pull just use your access token as password.