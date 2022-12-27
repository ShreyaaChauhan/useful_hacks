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
