## `git rebase`

ブランチのブランチの派生元の変更

#### 文法

```
git rebase [OPTION] BRANCH_NAME
```

#### 使い方

```
$ git checkout my_branch
$ touch file1
$ git add file1
$ git commit -m "Add file in my_branch"
$ git checkout master
$ touch file2
$ git add file2
$ git commit -m "Add file in master"
$ git checkout my_branch
$ touch file3
$ git add file3
$ git commit -m "Add file in my_branch"
$ git log
$ git rebase master
$ git log
```
