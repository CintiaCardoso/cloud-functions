gitGoogle cloud functions
# This file is a test
## Starting a project
Description test about README commit 3

##About command git:

```python
git init
git remote add origin https://github.com/{user.name}/{projet.name.git}
git config --global user.mail "{user.mail in git}"
git config --global unes.name "name in git"
```
then, when you add files, the command is:

 ```python
 git add .
 git commit -m "commit name"
 ```
venv in Windows
 ```
 pyhton3 -m venv .venv
 in .venv ejecute: Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
 in Scripts ejecute: .\activate
 in helloworld: functios-framework --target hello_world
  ```
inside the venv, ejecute google cloud skd:
```
in helloworld ejecute: gcloud init
if need change the project, ejecute: 
gcloud project list
gcloud config set project + "id the project"
```

To deploy cloud functions:
```
gcloud functions deploy "name function" (hello_world in this example) --runtime python 37 --trigger-http
```

  when finish, ejecute en Scripts:

```
.\deactivate.bat
```

