(first step when making a project)
Git:
- mkdir ProjectName (whatever you want)
- cd MyProject
- git init
- touch readme.md
 {put stuff in readme file}
- git add . 
- git commit -m "initial commit"
- Create repo on github and grab the ssh link 
    - looks like (but isnt) git@github.com:ariggs16/ProjectName.git
- Add our remote
    - git remote add origin @github.com:ariggs16/ProjectName.git
- git push origin master

(do over and over again)
- git add .
- git commit -m "add message"
- git push origin master