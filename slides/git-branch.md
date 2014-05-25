## `git branch`

ブランチ管理

#### 文法

```
git branch [OPTION]
```

#### 使い方

```
$ git branch
* master
$ git branch my_branch
$ git branch
  my_branch
* master
$ git branch old_branch
* master
  my_branch
  old_branch
$ git branch -d old_branch
$ git branch old_branch
* master
  my_branch
  ```
