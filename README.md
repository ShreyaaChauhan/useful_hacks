# Useful Hacks

## Creation of automatic requirements.txt file
```
pip install pipreqs
pipreqs /path/to/project
```

## Push your code in the past
`git commit --amend --date="$(date -v-2d)"`

## Remove current remote origin
`git remote rm origin`

## Get the path to parents folder
```python
import os
parent_folder_path = os.path.abspath(os.path.dirname(__file__))
```
## Unzip content in python 
```
import shutil
shutil.unpack_archive('/source_folder','/destination folder')
```
## Run notebooks from github colab to colab notebooks
Change 'github.com' to 'githubtocolab.com'

## Find processor architecture of your Mac.
``` uname -p ```

## Change default version of java on MAC
First get the list of all version of java installed on your mac by following command
``` /usr/libexec/java_home -V ```
Afterwards select the version of java by following command
``` export JAVA_HOME=`/usr/libexec/java_home -v 11.0 ```
where 11.0 can be replaced by the version of java you wants to set as default
