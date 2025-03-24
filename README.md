# gitmoji commit template

gitmoji を使用するためのコミットテンプレートです。探してみたのですが見当たらなかったため、作ってみました✨
2025/03/24 時点で [https://gitmoji.dev/](https://gitmoji.dev/) に掲載されているものをトレースしました。

基本的に、VSCodeの拡張機能の日本語化から合わせていますが、一部調整してあります。適宜追加/変更/削除などしてお使いください。
誤字等があった場合もご修正してお使いいただけると幸いです🙇

## globalに反映するコマンド

```bash
make global
```

## 解除したい場合

`~/.gitconfig`の以下の箇所を削除して下さい
~
[commit]
	template = /Users/your_name/.gitmoji_commit_template
~
