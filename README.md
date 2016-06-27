# something is more new

https://backlogtool.com/git-guide/kr/stepup/stepup1_5.html

## GitHub Forkしたブランチでフォーク元の差分を取り込む

1. local環境でforkしたブランチに移動

```
$ cd forkedLocalRepogitory
```

2. フォーク元のリポジトリ登録

```
$ git remote add forked_master git://github.com/foked/master.git
```

3. フォーク元の内容を取得、localのブランチにマージ

```
$ git fetch forked_master
$ git merge forked_master/master
```
