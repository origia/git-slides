## `git add`

レポジトリにファイル追加

#### 使い方

```
$ git add foo
On branch master
Initial commit
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

    new file:   foo
$ touch a b c
$ git add .
$ git status
On branch master
Initial commit
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

    new file:   a
    new file:   b
    new file:   foo
```
