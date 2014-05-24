## `ls`

ディレクトリの中身一覧

#### 文法

```
ls [OPTION] [FILE]
```

#### 使い方

```
$ ls
Desktop  Documents  Downloads  Dropbox  Templates  tmp  workspaces
$ ls workspaces
eclipse  go
$ ls -l ~/workspaces/
total 8
drwxr-xr-x 5 daniel daniel 4096 Apr 14 16:48 eclipse
drwxr-xr-x 5 daniel daniel 4096 Apr 14 16:48 go
$ ls -a workspaces
.  ..  eclipse  go
```
