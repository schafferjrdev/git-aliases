# Git Aliases

To add a new Alias just type

`git config --global alias.<alias name> '<git command>'`

To remove a Alias use this

`git config --global --unset alias.<alias name>`

Favorites Aliases

```
git config --global alias.tree 'log --all --decorate --oneline --graph'

git config --global alias.newbranch 'checkout -b'

git config --global alias.st 'status'

git config --global alias.aliases 'config --get-regexp alias'

git config --global alias.cm 'commit -m'

git config --global alias.olog 'log --oneline'

git config --global alias.set-alias 'config --global'

git config --global alias.remove 'restore --staged'

```
