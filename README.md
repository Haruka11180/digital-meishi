# digital-meishi

大木遥のデジタル名刺。1枚の `index.html` だけで動く静的ページです。

公開URL: https://haruka11180.github.io/digital-meishi/

## 編集のしかた

`index.html` の「▼▼▼ ここから名刺の中身 ▼▼▼」のブロックを書き換えて
main ブランチにプッシュすると、GitHub Actions が自動で公開ページを更新します。

- 名前・肩書き・自己紹介: `.card` 内のテキスト
- 連絡先・リンク: `.contacts` の行
- 「連絡先に保存」の中身: `.card` の `data-vcard-*` 属性
- 写真: `.avatar` の div を `<img class="avatar" src="photo.jpg" alt="">` に差し替え
