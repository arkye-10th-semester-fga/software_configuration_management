06/13/2017 - Monday

# Managing System Configuration

* Configuration Item
* Realization
	* Tools
		* Version Control System
		* Deploy Automation
		* Build Automation
	* Tasks
	* Who?
	* When?
	* Policies
		* Tool Access
		* Version Control
		* Names
* Sharing Policies
	* Work's Copy
	* Lock-Modify-Unlock
	* Copy-Modify-Solve
* Main Features
	* Control different versions
	* Register changes
	* Allows teamwork
	* Allow branches
* Repository
	* Save files
	* Remote (Server)
	* Save configurations
	* Save all versions

# Git Practice

```Shell
mkdir myrepo
cd myrepo
git init
tree -a .
cd ..
git clone http://... myreponame
git remote -v
git remote add origin http://...
git remote rm origin
git remote rename origin main
git status
touch README.md
git add README.md
touch deps/description.md
git add deps/description.md
git commit -m "Initial Commit"
git log --oneline
git diff
git diff --cached
git show <hash>
git add -p .
git add -u
git rm
git stash
git stash list
git stash pop
git stash apply stash@{0}
git stash drop
git clean -f
git checkout -b my_feature
git branch
git branch -a
git push origin master:my_remote_branch
git branch -d my_branch
git fetch origin
git pull origin branch
git pull --rebase origin branch
git merge master
git diff master my_branch
git rebase master
git tag v1.0.0 COMMIT_HASH
git tag -l
git tag -d v1.0.0
git checkout .
git checkout -p .
git reset --hard origin/master
git config color.ui true
git config format.pretty oneline
git config user.email ""
git config user.name ""
git config --global core.editor ""
git config --global commit.template /path/to/git-commit-template.txt
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
'''.git/hooks/pre-commit
pre-commit
post-commit
'''.gitattributes
```
