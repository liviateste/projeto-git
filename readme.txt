git config --global user.name "Livia Teste"
git config --global user.email "liviakarolayne.extra@gmail.com"
git config --local user.name "Livia Teste"
git config --local user.email "liviakarolayne.extra@gmail.com"
git config user.email
git config user.name
git init
git init --bare
git status
git add
git commit
git log
git log --oneline
git log -p
git log --pretty="format:%H"
git log --help
git remote
git remote -v
git remote add servidor /home/livia/Workspace/git/servidor
git remote add origin https://github.com/liviateste/projeto-git.git
git clone /home/livia/Workspace/git/servidor projeto
git remote rename origin servidor
git push servidor master
git pull servidor master
git branch
git branch titulo
git checkout titulo
git checkout -b lista
git merge titulo

https://devhints.io/git-log
https://git-school.github.io/visualizing-git/