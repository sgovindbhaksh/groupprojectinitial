----------------------------------------------------
# Github and Cloud9 setup using Personal Access Token:
----------------------------------------------------- 
1. Login Github and Create a repository
2. get familiar with account profile --> settings -->Developer Settings -->Personal Access Tokens 
3. Click "Generate New Token" 
   a. Provide a Note such as "CIS5755"
   a. Select Expiration Date
   a. Select scopes
4. Click "Generate token", copy and paste the token in a temporary place
5. Create a new cloud9 environment
6. Delete the README.md file
7. git config --global credential.helper store
8. Go to Github and copy the repository URL
8. Go to Cloud9 terminal and clone the repository
   a. Type: git clone + repository URL
   a. enter your github username
   a. Copy and paste teh token for password
9. Change directory to the new folder
10. Create a project directory (e.g. mkdir Chapter-1)
11. Change to the new directory
12. Create python envionrment: python3 -m venv env
13. To activate the envionrment: source env/bin/activate
14. Create a python file named ex1-print.py
15. Edit the python file
    a. Open the file
    a. Enter a line of code
    a. Run the file
16. While keeping the current terminal window for project,  open a new terminal for git to manage the source code) 

18. git add --all
19. git status
20. git commit -m "first python code"
21. git push
    a. github username:
    a. password: copy and paste the account access token
22. check the changes by using: git log
23. Go to Github repository to check the changes
24. Go to Cloud9 and create a second python file: ex2-flask.py
25. Edit the file by copy/paste the basic Flask code
26. Save and Run the file
27. In the terminal, install Flask package (library): python3 -m pip install flask
28. In the terminal, run the file: python3 ex2-flask.py
29. To view the app, go to Tools menu, select Preview --> Preview Running App
30. To stop the service, press Ctrl + C
31. In the git terminal, enter command step 17-21
    a. change commit comment to "First Flask example"

30. Create an instruction markdown file for Chapter 1
    a. Edit the file by copy/paste this lab instructions
    a. Add basic markdown styles
    a. Save the file
31. In the git terminal, enter command step 17-21
    a. change commit comment to "First Instruction File"