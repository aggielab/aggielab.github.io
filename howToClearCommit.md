當你想要重設 commit 的紀錄時，你可以使用以下的指令:  

```shell
git checkout --orphan new_branch

git add .

git commit -m "Remove history commit."

git branch -D master

git branch -m master

git push -f origin master

```
by Dinlon5566  