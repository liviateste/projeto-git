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
git log --graph
git log --help
git remote
git remote -v
git remote add servidor /home/livia/Workspace/git/servidor
git remote add origin https://github.com/liviateste/projeto-git.git
git clone /home/livia/Workspace/git/servidor projeto
git remote rename origin servidor
git push servidor master
git push servidor v.0.1.0
git pull servidor master
git branch
git branch titulo
git checkout titulo
git checkout -b lista
git checkout -- <file>
git merge titulo
git rebase lista
git rebase -i HEAD~3
git reset HEAD
git revert <hash>
git cherry-pick <hasj>
git stash
git stash list
git stash appy 0
git stash drop
git stash pop
git diff
git diff <hash>..<hash>
git tag -a v0.1.0
git tag -a v0.1.0 -m "Lançando a primeira versão"
git bisect start
git bisect bas HEAD
git bisect good <hash>
git blame

Hooks

branches:
    desenvolvimento
        feature/<name>
    teste
    conseto de erro
    versões
git flow
    git cola - https://git-cola.github.io/
    git desktop - https://desktop.github.com/
    git kraken - http://www.gitkraken.com/

https://devhints.io/git-log
https://git-school.github.io/visualizing-git/