# KTR_LyricMV

歌詞アニメーションのミュージックビデオを作る Windows 用の無料ソフトです。
曲を読み込み、拍に合わせて歌詞を並べ、文字の見た目と動きを付けて MP4 に書き出せます。

このリポジトリは**配布用**です。ダウンロードは Releases からどうぞ。

## ダウンロード

**[最新版のダウンロードページ](https://github.com/KTR-Shibata/KTR_LyricMV-releases/releases/latest)**

| ファイル | 内容 |
|---|---|
| `KTR_LyricMV-<版>-setup.exe` | インストーラー版（おすすめ）。管理者権限なしでインストールできます |
| `KTR_LyricMV-<版>-win-x64.zip` | zip 版。好きな場所に展開して `KTR_LyricMV.exe` を起動します |

どちらにも使い方ガイド（`KTR_LyricMV_Manual.html`）が入っています。

## 動作環境

- Windows 10 / 11（64 ビット）
- .NET は同梱しているので、別のインストールは不要です
- **動画の書き出しと動画素材の読み込みには [ffmpeg](https://ffmpeg.org/download.html) が必要です**（同梱していません）。
  準備の手順は、ダウンロードしたファイルの中の `README.txt` と使い方ガイドにあります

## はじめて起動するとき

コード署名をしていないため「Windows によって PC が保護されました」と表示されることがあります。
「詳細情報」→「実行」で起動できます。

ダウンロードしたファイルが本物かどうかは、各リリースに載せている SHA-256 と照らし合わせて確かめられます。

```
certutil -hashfile KTR_LyricMV-<版>-setup.exe SHA256
```

## 同梱ソフトウェア

.NET、SkiaSharp（Skia）、NAudio、OpenTK を同梱しています。ライセンス表記は、ダウンロードしたファイルの中の
`THIRD-PARTY-NOTICES.txt` をご覧ください。

## 免責事項

本ソフトウェアは無償で提供するもので、動作・品質・特定の目的への適合性などについて、いかなる保証もいたしません。
本ソフトウェアの使用または使用できなかったことによって生じたいかなる損害（データの消失、プロジェクトや作成した動画の
破損、パソコンの不具合などを含みます）についても、作者は一切の責任を負いません。ご利用は利用者ご自身の責任でお願いします。

This software is provided free of charge, "as is", without warranty of any kind. The author accepts no liability
for any damage arising from its use or inability to use it, including loss of data or damage to projects or videos.
Use it at your own risk.
