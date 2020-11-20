git statement

B1. 
1. git init
2. git status
3. git add 
	ex: 
		git add .
		git add mouse.js
4. git commit
	ex: 
		git commit mouse.js -m"..write something"
		git commit -m"..write something"

B2.
1. git log
2. git show <id>
3. git diff

B3.
1. git checkout -- <filename, .>
2. git reset <filename, .>
3. git restore, git restore --staged <filename, .>

B4. 
1. git branch
2. git checkout -b feature/login
3. git checkout

1. git checkout master
2. git merge feature/login
3. git branch -d feature/login

B5.
1. git reset --soft <to-commit>
2. git reset --mixed <to-commit>
3. git reset --hard <to-commit>

B6.
1. git revert <commit>

B7. 
1. gitignore

B8.
1. one code, one watch: push and pull
2. code team (pull request: muốn branch mình merge to main)
	1.	git checkout -b <branch>
	2.	git push origin <branch> (tab)
	3.	create a pull request on Github
		3.1 code -> branch -> new pull request
	4.	review code
		4.1. online
		4.2. offline git fetch origin <branch>
	5.	merge to master (convertions -> merge)

B9.


git area 

1. working directory
2. staging area
3. git repos


terminal
q
git update