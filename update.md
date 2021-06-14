```
git remote add upstream https://github.com/nsz32/docklike-plugin.git
git fetch upstream
git checkout master && git reset --hard upstream/master && git push
git checkout gsantner-personal && git merge master ; git rebase master
```
