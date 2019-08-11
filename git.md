**Installing git**

`sudo apt-get install git` 

**Going to project folder**

`cd Desktop/projects/scripts`

**Entering email and user name**

`git config --global user.email "vasko.vlad.2006@gmail.com"`

`git config --global user.name "VlaDosWOW"`

**Commiting first commi**

`git commit -m "1st commit"`

**Watching status of local repository**

`git status`

**Wathing history of repository**

`git log`

**Wathing difference of local and GitHub repository**

`git diff`

`nano README.md`

`git add .`

`git commit -m "2nd commit"`

`echo "# scripts" >> README.md`

`nano README.md`

`git status`

`git remote add origin git@github.com:VlaDosWOW/scripts.git`

`git push origin master`

`git pull`

`nano README.md`

`git branch --set-upstream-to=origin/master master`

`git pull`


