# git 入門

## 課題 1. コミットしてみよう

hello.txt がある

1. プロジェクトフォルダ内に `hello.txt` を作成する
2. `hello.txt` に `hello world` を書き込む
3. 変更をコミットする
   1. ステージングに上げて `git add`
   2. `git commit` する
4. push する

## 課題 2. ブランチを作成してみよう

1. `my-branch` ブランチを作成する
2. `my-branch` に checkout する
3. `my-branch` ブランチを push する

<details>
<summary>git コマンド</summary>

```
git branch my-branch
git checkout my-branch
git push origin my-branch:my-branch
```

汎用コマンド `git push origin HEAD -u`

</details>
