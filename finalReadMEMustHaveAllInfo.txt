git checkout main
git pull

git branch addRefs
git checkout addRefs

git commit -m "added reference files for folders"
git add *
git push -u origin addRefs



todelete:
git branch -d addFolder