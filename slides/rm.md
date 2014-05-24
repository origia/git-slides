## `rm`

ファイル・ディレクトリの削除

#### 文法

```
rm [OPTION] FILE
```

#### 使い方

```
$ ls
file2  bar
$ rm file2
$ ls
bar
$ rm bar
rm: cannot remove ‘bar’: Is a directory
$ ls
bar
$ rm -r bar
$ ls
```
