# Feature-Branch-workflow
This is a FeatureBranch work flow

5. cd Feature-branch-wf-new/
   mkdir Settings
   mkdir Src
6. touch Settings/settings.json
7. touch .gitignore
   echo "Settings/" >> .gitignore 
   echo "*.log"  >> .gitignore
8. git checkout -b feature/index
   touch Src/index.html
   git add .
   git commit -m "created index.html file"
9. git add .
    git commit -m "updated  index.html file"
     git push -u origin feature/Index
10. git checkout -b feature/login
    touch Src/login.html
    git add .
    git commit -m "created login.html file"
11. git add .
    git commit -m "updated  login.html file"
      git push -u origin feature/login
12.git checkout -b feature/signup 
    touch Src/Signup.html
    git add .
    git commit -m "created signup.html file"
13. git add .
    git commit -m "updated  signup.html file"
    git push -u origin feature/signup

 
