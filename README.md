# w-rep
## git コマンド
** よく使うgitコマンド **
・リモートブランチからローカルブランチにcheckoutする
```
git checkout <branch>
```

・新しいブランチを作成する
```
git checkout -b <new branch>
```

・ローカルブランチを削除する
```
git branch -D <branch>
```

・ローカルブランチを最新化する
```
git pull
```

・ローカルブランチの状態を確認する
```
git status
```

・変更点を更新対象に含める
＊`.`これはカレントディレクトリ配下の変更点を全て対象とする
```
git add <file path>
git add .
```

・更新を確定させる
＊`-m`オプションを使用することでコミットする際にメッセージを追加することが可能
```
git commit
git commit -m "ここにコミットメッセージ"
```

・確定した更新内容をリモートブランチに反映させる
```
git push origin <branch>
```
