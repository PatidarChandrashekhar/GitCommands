
## This the Git command list ##

**1. Creating new branch from existing one**
* git checkout -b dev
* git push
* git push --set-upstream origin dev


**2. Commiting the code**
* git add . 
* git status -s
* git branch -a
* git commit -m "my commit"
* git push -u origin dev


**3. Creating the version**
* git checkout master
* git merge dev
* git push
* git tag -a v1.2 -m "version V1.2"
* git push --tags

 
**4. Proxy settings**
* npm config set strict-ssl false
* npm config set proxy http://proxy.patidar.com:8080/
* npm config set https-proxy http://proxy.patidar.com:8080/


**5. Deleting the remote branch**
* git push origin --delete dev


**6. Debugging the unit test case**
* "test": "mocha test/api/controllers/patidar.js --debug-brk"


**7. Attaching new drive to system**
* subst g: C:\MySettings



