GitSetup
========

##Copy this to ~Home/.gitconfig
[alias]  
	hist = log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short  
##Setup
* Create new repository over GitHub web  
Name it as GitSetup  
* Clone to local  
Double click GitShell icon  
cd D:\Repo (or folder that you want to keep App)  
git clone https://github.com/YayaKanlaya/GitSetup.git  
* Create a new file  
cd D:\Repo\Gitsetup  
notepad README.md and edit any text as you want  
* Commit to local  
git add README.md  
git commit -m "First commit"  
* Push to GitHub  
git push  


