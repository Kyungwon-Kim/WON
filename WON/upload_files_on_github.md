## Way to upload files on github
**_Initialization_**
1. Start Git
```
1. Sign up https://github.com/login  

2. Click "Start a project"  

3. Write the name of local repository ex) tutorial-git
```
2. Connect local pc between github
```
1. Make folder  
$ mkdir folder_name  

2. Move to generated folder  
$ cd folder_name  

3. Personal information settings  
$ git config --global user.name "Kyungwon"  
$ git config --global user.email "gmkgw93@gmail.com"  
```
3. Upload the file on github  
```
1. Initialize 'git'
$ git init  
./folder_name/.git will be created.  

2. Set the own github name(address) to origin  
$ git remote add origin https://github.com/KyungwonKim428/tutorial-git.git  

3. Check if there are any changes (Check the synchronization of local folder and data on git)  
$ git status  

4. Add file  
$ git add .  
or  
$ git add file_name  

5. Check the changed log  
$ git log  
**"fatal: your current branch 'master' does not have any commits yet"** message will appear.  

6. Commit the file  
$ git commit -m "_comment_"  

7. Push to master  
$ git push origin master  
Github username and password should be entered.
```
