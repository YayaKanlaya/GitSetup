GitSetup
========

Copy this to ~Home/.gitconfig
===============================
[alias]
  hist = log --pretty=format:'%h %ad | %s%d [%an]' --graph --date=short

Setup
=====
1. Create new repository over GitHub web
- Name it as GitSetup
2. Clone to local
- Double click GitShell icon
- cd D:\Repo (or folder that you want to keep App)
- git clone https://github.com/YayaKanlaya/GitSetup.git
3. Create a new file
- cd D:\Repo\Gitsetup
- notepad README.md and edit any text as you want
4. Commit to local
- git add README.md
- git commit -m "First commit"
5. Push to GitHub
- git push https://github.com/YayaKanlaya/GitSetup.git

