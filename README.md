Steps to using this template to create a new project

1. Navigate to root folder - cd /home/gerrypidgeondev
2. Clone the BlankProject repository. This will create a new directory called <new-repository-name> -
   git clone https://github.com/gerry-pidgeon-dev/BlankProject.git <new-repository-name>
3. Navigate to <new-repository-name> - cd <new-repository-name>
4. Remove Git History to Start Fresh - rm -rf .git
5. Initialize a New Git Repository - git init
6. Add a New Remote Repository - git remote add origin https://github.com/gerry-pidgeon-dev/<new-repository-name>.git
7. Add files to staging area - git add .
8. Commit the staged changes - git commit -m "first commit"
9. Renames current branch to main - git branch -M main
10. Pushes project to GitHub - git push -u origin main
