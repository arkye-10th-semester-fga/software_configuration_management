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
git commit -m "Initial Commit" ""
```
