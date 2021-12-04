----------------------------------------------------
# Github and Cloud9 setup using Personal Access Token:
----------------------------------------------------- 
1. Login Github and Create a repository
1. get familiar with account profile --> settings -->Developer Settings -->Personal Access Tokens 
1. Click "Generate New Token" 
   1. Provide a Note such as "CIS5755"
   1. Select Expiration Date
   1. Select scopes
1. Click "Generate token", copy and paste the token in a temporary place
1. Create a new cloud9 environment
1. Delete the README.md file
1. git config --global credential.helper store
1. Go to Github and copy the repository URL
1. Go to Cloud9 terminal and clone the repository
   1. Type: git clone + repository URL
   1. enter your github username
   1. Copy and paste teh token for password
1. Change directory to the new folder
1. Create a project directory (e.g. mkdir Chapter-1)
1. Change to the new directory
1. Create python envionrment: python3 -m venv env
1. To activate the envionrment: source env/bin/activate
1. Create a python file named ex1-print.py
1. Edit the python file
    1. Open the file
    1. Enter a line of code
    1. Run the file
1. While keeping the current terminal window for project,  open a new terminal for git to manage the source code) 

1. git add --all
1. git status
1. git commit -m "first python code"
1. git push
    1. github username:
    1. password: copy and paste the account access token
1. check the changes by using: git log
1. Go to Github repository to check the changes
1. Go to Cloud9 and create a second python file: ex2-flask.py
1. Edit the file by copy/paste the basic Flask code
1. Save and Run the file
1. In the terminal, install Flask package (library): python3 -m pip install flask
1. In the terminal, run the file: python3 ex2-flask.py
1. To view the app, go to Tools menu, select Preview --> Preview Running App
1. To stop the service, press Ctrl + C
1. In the git terminal, enter command step 17-21
    1. change commit comment to "First Flask example"

1. Create an instruction markdown file for Chapter 1
    1. Edit the file by copy/paste this lab instructions
    1. Add basic markdown styles
    1. Save the file
1. In the git terminal, enter command step 17-21
    1. change commit comment to "First Instruction File"