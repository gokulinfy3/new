....or create a new repository on the command line

echo "# new" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/gokulinfy3/new.git
git push -u origin main

....or push an existing repository from the command line

git remote add origin https://github.com/gokulinfy3/new.git
git branch -M main
git push -u origin main


what i do..

1. open cmd
2. go to location "cd .."
3. type> git init
4. dir > file.txt (to create new file)
5. git status
6. git add file.txt (to add)  or git add . (to add everything)
7. git commit -m "any message"  (to commit)
8. git remote add origin <link from github>  "https://github.com/gokulinfy3/new.git"
9. git push -u origin master  (to push)	
	# git config --global user.email "gokul.infy3@gmail.com"
	# git config --global user.name "gokulinfy3"	
10. git branch Branch1
11. git checkout Branch1
