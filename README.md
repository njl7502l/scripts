# scripts

.zshrcに色々おいてたけどごちゃごちゃしてきたのでまとめる。
自分用に色々作ったスクリプト置き場。
push前にshellcheckかけるようにする。

## 導入
実行権限付与
```
$ chmod +x <filename>
```
パスを通す
```
$ mv <filename> /usr/local/bin
```

## commands
### dirhash
```
$ dirhash <dirname>
a430105ab3b9e09fea9b8991f918c18d9155b531
```
ディレクトリの中のファイルに対して再帰的にhashかけてその出力のhashを出力する。
大きいディレクトリでやると時間かかるので注意。
