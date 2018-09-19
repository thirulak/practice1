# github practice session
commands:
 * mkdir ra(directoryname)
 
 * cd ra
 
 * dir>re.txt(file is created)
 
 * git init
 
 * git add .
 
 * git commit -m "first commit"
 
 * git remote add origin "git_repo_link"
 
 * git status
 
 * git push origin master
 
 * touch README.md
 * nano README.md
 * A terminal window opens where we can type our text to be displayed in the README page 
 * If you want to save the changes you've made, press Ctrl + O. To exit nano, type Ctrl + X. If you ask nano to exit from a modified file,    it will ask you if you want to save it. Just press N in case you don't, or Y in case you do. It will then ask you for a filename. Just      type it in and press Enter.
 * https://wiki.gentoo.org/wiki/Nano/Basics_Guide 
 * git commit -m "second commit"
 * git status
 * git remote add origin "git_repo_link"
 * git push origin master
 * To resolve the unrelated histories encountered during git pull use "git pull origin master --allow-unrelated-histories" 
 * https://stackoverflow.com/questions/37937984/git-refusing-to-merge-unrelated-histories-on-rebase 
 ## How to add README.md to an empty repository : 
 * echo "# repo_name" >> README.md
 * git init
 * git add README.md
 * git commit -m "first commit"
 * git remote add origin repo_link.git
 * git push -u origin master
       
