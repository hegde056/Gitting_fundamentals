# Learning Git Basics

 ***hegde056***

Hello-World !!!

Helpful commands : 

git config --global user.name "Mr.Bean"
git config --global user.email "abc@xyz.com"

***create new folder***

git init 
touch readMe.md				--> creates readMe file
git status
git add readMe.md			--> to add all untraked files : "git add ."
git commit  -m "Commit message"

git log 
touch .gitignore
git add .gitignore
git commit  -m "Commit message"		

####First time generating ssh keys and adding to GitHub
ssh-keygen -t rsa -b 4096
eval "$(ssh-agaent -s)"
ssh-add /c/Users/Mr.Bean/.ssh/id_rsa
clip < /c/Users/Mr.Bean/.ssh/id_rsa.pub
####in Github go to profile settings > SSH keys > add new > give name and paste the key 


git remote add origin git@github.com:hegde056/Gitting_fundamentals.git
git push -u origin master

git clone git@github.com:hegde056/Gitting_fundamentals.git CustomizedFolderName    --> CustomizedFolderName if need to clone with different folder name

git pull 
git push 
