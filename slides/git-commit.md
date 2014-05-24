## `git commit`

新しいコミットの作成

#### 文法

```
git commit [OPTION]
git commit -m "MESSAGE"
git commit -am "MESSAGE"
```

#### 使い方

```
$ git commit -m "Initial commit"
[master (root-commit) 5a21c43] Initial commit.
 4 files changed, 0 insertions(+), 0 deletions(-)
.....
$ echo a >> c
$ git commit -m "Change c"
On branch master
Changes not staged for commit:
    modified:   c
no changes added to commit
$ git commit -am "Change c"
[master c7cd65c] Change c
 1 file changed, 1 insertion(+)
```
