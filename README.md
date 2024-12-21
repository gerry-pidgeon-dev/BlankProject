Steps to Using This Template to Create a New Project

1. Navigate to the root folder:
   cd /home/gerrypidgeondev

2. Clone the BlankProject repository. This will create a new directory called <new-project-name>:
   git clone https://github.com/gerry-pidgeon-dev/BlankProject.git <new-project-name>

3. Navigate to <new-project-name>:
   cd <new-project-name>

4. Remove Git history to start fresh:
   rm -rf .git

5. Initialize a new Git repository:
   git init

6. Add a new remote repository:
   git remote add origin https://github.com/gerry-pidgeon-dev/<new-project-name>.git

7. Add a new repository on GitHub:
   gh repo create <new-project-name> --public

8. Clear the README.md file:
   > README.md (Or use: truncate -s 0 README.md)

9. Add files to the staging area:
   git add .

10. Commit the staged changes:
   git commit -m "first commit"

11. Rename the current branch to main:
    git branch -M main

12. Push the project to GitHub:
    git push -u origin main
