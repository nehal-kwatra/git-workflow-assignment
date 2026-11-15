GIT & GITHUB WORKFLOW ASSIGNMENT
Student: Yuvraj Kwatra
Registration Number: 2024EB01368

FILES
- index.html       Home page
- about.html       About page
- .gitignore       Ignores *.log files and the temp/ folder
- git_commands.txt Git commands and short explanations

THIS FOLDER CONTAINS A LOCAL GIT REPOSITORY
The .git directory is included in the ZIP and contains the commit history and
main/feature branches created for the assignment.

TO CONNECT THIS REPOSITORY TO YOUR OWN PUBLIC GITHUB REPOSITORY
1. Sign in to GitHub and create a NEW public repository named:
   git-workflow-assignment
2. Do not select "Add a README", .gitignore, or license on GitHub.
3. Open a terminal in this extracted folder.
4. Run the following commands, replacing YOUR-USERNAME:

   git remote add origin https://github.com/YOUR-USERNAME/git-workflow-assignment.git
   git push -u origin main
   git push -u origin feature

5. Open the GitHub repository in a browser and check that both branches and
   the commit history are visible.
6. Copy the actual public repository URL into the assignment PDF.

USEFUL VERIFICATION COMMANDS
   git branch -a
   git log --oneline --graph --decorate --all
   git status
   git remote -v

IMPORTANT
This is a prepared local project folder. You still need to create your own
public GitHub repository and push the branches from your computer.
