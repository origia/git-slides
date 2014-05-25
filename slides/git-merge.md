## `git merge`

ブランチのマージ

#### 文法

```
git merge [OPTION] BRANCH_NAME
```

#### 使い方

```
$ touch foobar
$ git add foobar
$ git commit -m "Add foobar"
$ git log
$ git checkout master
$ git branch
* master
  my_branch
$ git log
$ git merge my_branch
Updating e7ace72..08b4293
....
$ git log
```
