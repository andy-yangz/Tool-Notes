# Git Notes

#### 当想要追踪repo自己开发的话

```
git clone git@github.com:<YOUR-USERNAME>/<REPO>.git
git remote add upstream git@github.com:<REPO>.git

#每次开发前，同步最新更新
git fetch upstream
git checkout main
git merge upstream/main
git push origin main
```