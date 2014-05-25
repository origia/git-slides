## `git remote`

リモートの管理

#### 文法

少し複雑なので,

```
$ man git-remote
```

#### 使い方

今回、Githubに上げられるようにする。

```
$ git remote add origin URL
$ git remote show origin
* remote origin
  Fetch URL: git@github.com:origia/git-slides.git
  Push  URL: git@github.com:origia/git-slides.git
  HEAD branch: master
  Remote branch:
    master tracked
  Local branch configured for 'git pull':
    master merges with remote master
  Local ref configured for 'git push':
    master pushes to master (up to date)
```
