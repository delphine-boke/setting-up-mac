when you have worked on a project locally and would like to have it hosted on either GitLab or GitHub, then follow these steps:

i. initialise your folder by running

``git init . ``

ii. then add contents of your folder

``git add . ``

iii. now, you have to have a commit message e.g

``git commit -m "initial commit"``

iv. when you proceed directly and do a 

``git push origin main``

you will get a 
```
fatal: 'origin' does not appear to be a git repository
fatal: Could not read from remote repository.

Please make sure you have the correct access rights and the repository exists.
```

error message.

v. you would want to proceed to your profile on either GitLab or GitHub, create a new repo and copy that said url.

vi. after the copying of the url, do this

``git remote add origin <link to repo>``

vii. finally, do a push 

``git push -u origin main``
