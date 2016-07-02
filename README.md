複数のマシンでAtom設定を同期するための設定

## パッケージのインストール
``` shell
$ apm install --packages-file packages.txt
```

## インストールしているパッケージの情報リストを作成(更新も)
※パッケージを追加や削除した場合も実行する

``` shell
$ apm list --installed --bare > packages.txt
```

## Download

https://atom.io/

## よく使うコマンドリスト

### カレントディレクトリでアプリ起動

``` shell
atom .
```
