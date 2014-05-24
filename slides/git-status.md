## `git status`

レポジトリの状態確認

#### 使い方

```
$ git status
On branch master
Initial commit
nothing to commit (create/copy files and use "git add" to track)
$ touch foo
$ mkdir bar
$ git status
On branch master
Initial commit
Untracked files:
  (use "git add <file>..." to include in what will be committed)

    foo

nothing added to commit but untracked files present (use "git add" to track)
```
