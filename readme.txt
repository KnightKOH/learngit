Git is a free software.
git add
git commit -m " "
git stash
git stash pop
git cherry-pick
git merge --no-ff -m "" nthnth

git remote
git remote v

git tag
git tag <tagname>
git tag -a <tagname> -m "balalala"
git push origin <tagname>
git push origin --tags
git tag -d <tagname>
git push origin :refs/tags/<tagname>

git .gitignore

git config --global alias.st states
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.br branch
git config --global alias.unstage 'reset HEAD'
git config --global alias.last 'log -1'
git config --global alias.lg "log --color --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
