## `mv`

ファイル・ディレクトリの移動

#### 文法

```
mv [OPTION] SOURCE DEST
```

#### 使い方

```
$ mkdir empty_dir
$ cd empty_dir
$ touch file1
$ ls
file1
$ mv file1 file2
$ ls
file2
$ mkdir foo
$ mv foo bar
$ ls
file2  bar
```
