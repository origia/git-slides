## `cp`

ファイル・ディレクトリのコピー

#### 文法

```
cp [OPTION] SOURCE DEST
```

#### 使い方

```
$ mkdir empty_dir
$ cd empty_dir
$ touch file1
$ ls
file1
$ cp file1 file2
$ ls
file1  file2
$ mkdir foo
$ cp foo bar
cp: omitting directory ‘foo’
$ ls
file1  file2  foo
$ cp -r foo bar
$ ls
bar  file1  file2  foo
```
