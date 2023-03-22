## よく使うコマンド

### 最初に
```bash
$ gh repo clone xxx/xxx
```

```bash
$ gh repo sync
```

### 開発時
```bash
$ gh issue create
```

```bash
$ gh issue list
```

```bash
$ gh issue develop xx -c
```

->開発完了したら
`git add .`, `git commit -m "hoge"`, `git push`
した後に

```bash
$ gh pr create
```

```bash
$ gh browse
```


### リポジトリ検索（forkしていないpublicリポジトリ限定）

```bash
$ gh repo list --source --visibillity=public [username]
```

