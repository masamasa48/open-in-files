# open-in-files

Discord など **https のリンクしか押せない場所**から、iPhone の「ファイル」アプリで
iCloud Drive のフォルダを開くための中継ページ。

```
https://masamasa48.github.io/open-in-files/#<iCloud Drive からの相対パス（区切りごとにURLエンコード）>
```

ページは `shareddocuments:///private/var/mobile/Library/Mobile%20Documents/com~apple~CloudDocs/<パス>`
へ移動するだけ。`#` 以降はサーバーに送られないので、フォルダ名がアクセスログに残ることはない。
開く先は iCloud Drive の中に限っている（ほかのサイトへ転送はしない）。
