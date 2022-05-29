# version 1.0

```
git init #本地仓库
git add doc.md #添加文件到仓库
git commit -m "commit doc.md" #提交文件
```

# version 2.0

```
git status #查看状态
git add filename #提交修改
git restore filename #discard changes
git diff #查看修改
```

# version 3.0

```
git reset --hard commit_id #回退版本， HEAD,HEAD^,HEAD^^,HEAD~100
git log # commit log
git reflog # command log
git log --graph --pretty=oneline --abbrev-commit
```
# version 4.0
```
缓存区 ↔ 库(HEAD)：git diff --cached

工作区 ↔ 缓存区：git diff

工作区 ↔ 库(HEAD)：git diff HEAD -- filename

库 ↔ 库：git diff 243550a 24bc01b filename     #较旧的id 较新的id
```
# version 5.0
```
git remote add origin git@github.com:DimariaW/git-learning-doc.git #远程仓库关联
git branch -M main #当前分支改名
git push -u origin main #推送
```

# branch

```
git branch dev #create dev branch
git switch dev #switch to dev
git branch [-r-a] #list all or remote or local branches
git branch [-v-vv] # see branch relations
git merge dev: main 分支merge dev分支
```
# restore
```
git restore file : 撤销工作区的修改，同步至到暂存区
git restore --staged file: 撤销暂存区的修改，到版本库
```