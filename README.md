# hellocodingschool-archive

## Githubのリポジトリを作成する

## Git cloneをする

ローカル環境にリポジトリを複製するコマンド

```sh
% git clone リポジトリURL
```

## gitignore

.gitignoreファイルを作成することでgit対象からファイルを外す

```sh
% echo ".DS_Store" > .gitignore
```

## git add コマンド

ファイルの中身をインデックスに追加する

```sh
% git add .
```

## git commit

git commit は、追加、変更したファイルをGitに登録するためのコマンドをします。

```sh
% git commit -m "firstcommit"
```

## git push

main ブランチにpushする

```sh
% git push origin main
```

## 公開ブランチを作成する

## Github Pagesの公開設定をする

Settings タブを選択する。

左サイドバーにある Code and automation にある、Pages を選択する。

GitHub Pages　の一覧から、None をクリックして、mainを選択して、Saveをクリックします。

数分程度待つとデプロイされ、公開したWebページのURLが表示されます。

URLにアクセスすると、Webページを確認することができると思います。