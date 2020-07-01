# starter-project-gulp

Starter project for new project with gulp and scss and browser-sync

## 1. Clone repo

### GitHub

```
git clone git@github.com:giao/starter-project-gulp.git MY_NEW_PROJECT
```

### GitLab

```
git clone git@gitlab.com:giao.dinh/starter-project-gulp.git MY_NEW_PROJEC
```

## 2. Install npm modules

```
npm install --save-dev gulp gulp-sass browser-sync
```

## 3. Configure project

modify package.json accordingly

## 4. Init gulp

gulp style
gulp watch

## 5. Gitify the new project

* Create upstream repos (GitHub && GitLab)
* git init local project
  ``` 
  $> rm -fr .git
  $> git init
  $> echo "# MY_NEW_PROJET" >README.md
  $> git commit -a -m "First commit"
  $> git remote add ghub git@github.com:giao/MY_NEW_PROJECT.git
  $> git remote add glab git@gitlab.com:giao.dinh/MY_NEW_PROJECT.git
  $> for rmotes in ghub glab ; do git push -u $rmotes master ; done
  ```