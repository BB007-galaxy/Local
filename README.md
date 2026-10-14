# steps to run git

git --version

git clone https://github.com/BB007-galaxy/Sample1.git

cd Sample1
 
ls -a

git status

git add .

git commit -m "FIRST COMMIT"

git push origin main

---------------------------------------------------------------------------------------

mkdir Local

cd Local

ls -a

git init

ls 

git status

git add .

git commit -m "4th commit"

git remote add origin https://github.com/BB007-galaxy/Local.git ->copy this URL from git hub

git remote -v

git branch 

git push origin main

the local folder (Local) == same in remote repo (Local)

----------------------------------------------------------------------------------------------------------------------

git branch

git checkout -b feature1

git checkout main

git checkout -b frature2

git branch -d frature2

git push origin feature1

git diff main

git pull origin main

git merge main

git merge feature1