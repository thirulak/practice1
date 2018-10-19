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
 * If you want to save the changes you've made, press Ctrl + O. To exit nano, type Ctrl + X. If you ask nano to exit from a modified   file, it will ask you if you want to save it. Just press N in case you don't, or Y in case you do. It will then ask you for a filename. Just type it in and press Enter.
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
 * _the -u flag adds a tracking reference to the upstream server you are pushing to_
 * https://stackoverflow.com/questions/5697750/what-exactly-does-the-u-do-git-push-u-origin-master-vs-git-push-origin-ma
 ### How to add Checkbox in README.md in Github : 
 https://stackoverflow.com/questions/47344571/how-to-draw-checkbox-or-tick-mark-in-github-markdown-table
 
 #### How to add images directly in README files :
* You can create a New Issue
* upload(drag & drop) images to it
* Copy the images URL and paste it into your README.md file.
- **Ref** : https://stackoverflow.com/questions/14494747/add-images-to-readme-md-on-github
- **Git ignore** : 
- https://www.youtube.com/watch?v=f3yQu7YepuE
- https://git-scm.com/docs/gitignore
- **Use of Gitignore**: .gitignore is created for ignoring file, it means , which you don’t want to track or don’t want to upload in github.

- When creating a new repository and in case of uploading folders from local machine dont check the _Initialize with a Readme file_ it may lead to merging conflicts or unrelated history errors. 
   - For more info : https://stackoverflow.com/questions/38255655/trying-to-pull-files-from-my-github-repository-refusing-to-merge-unrelated-his/40959920

- **How to delete a repo from Github :**
1. git rm -r directoryname
2. git status (To check if the changes are done)
3. git commit
4. git push origin master
   - https://superuser.com/questions/918317/how-to-delete-remove-files-from-a-pushed-commit
   
- What happens when you are working in a linux platform and your friend is working in Windows platform for a collab poject, how to avoid the line ending errors?
   - This is how did manages this https://stackoverflow.com/questions/5834014/lf-will-be-replaced-by-crlf-in-git-what-is-that-and-is-it-important
