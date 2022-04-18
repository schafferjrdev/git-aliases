# :rocket: Git Aliases 

## :hammer_and_wrench: To add a new Alias just type

`git config --global alias.<alias name> '<git command>'`

## :hammer_and_wrench: To remove a Alias use this

`git config --global --unset alias.<alias name>`

## :star: Favorites Aliases

Feel free to copy all of my favorite aliases and use it!

```
git config --global alias.tree log --all --decorate --oneline --graph

git config --global alias.st status

git config --global alias.aliases config --get-regexp alias

git config --global alias.olog log --oneline

git config --global alias.set-alias config --global

git config --global alias.unset-alias config --global --unset

git config --global alias.rescue !git fsck --full --no-reflogs --unreachable --lost-found | grep commit | cut -d\  -f3 | xargs -n 1 git log -n 1 --pretty=oneline > .git/lost-found.txt

git config --global alias.cam commit -am

git config --global alias.clr checkout .

git config --global alias.cb checkout -b

git config --global alias.pup push --set-upstream

git config --global alias.rs restore --staged .

git config --global alias.soft-one reset --soft HEAD~1

git config --global alias.hard-one reset --hard HEAD~1

git config --global alias.delete-ignored rm -rf --cached .

```
