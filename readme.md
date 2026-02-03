# このブランチについて

このブランチ（`kz_3.5.2_patch_feature`）は、登 大遊 氏のSumatraPDF（[dn_3.5.2_patch2](https://github.com/dnobori/DN-fork-sumatrapdf/tree/dn_3.5.2_patch2)）を基に、日本語縦書きにレイアウトされたPDFのために、**左から右に連続スクロール表示させる機能**を追加したバージョンになります。

## 対象バージョン

- ベースブランチ：[dn_3.5.2_patch2](https://github.com/dnobori/DN-fork-sumatrapdf/tree/dn_3.5.2_patch2)
- 対象 OS：Windows（Windows 11 で動作確認）

## 追加した機能

日本語縦書き PDF に対して**左 → 右方向の横スクロール表示**を行う機能を追加しました。

## 使い方

「表示」→「横スクロール（左→右）」を選択してください。

[![Image from Gyazo](https://i.gyazo.com/4fd2a52226fc7a1c7911d8dfd4a748f1.png)](https://i.gyazo.com/4fd2a52226fc7a1c7911d8dfd4a748f1.png)

左から右に横スクロール表示されます。

[![Image from Gyazo](https://i.gyazo.com/0d3857ebf462d703b5ba7884424fa4d5.png)](https://i.gyazo.com/0d3857ebf462d703b5ba7884424fa4d5.png)

## 想定用途と制限

- 日本語縦書き PDF を主対象としています。
- 横書き PDF や特殊なレイアウト（異なるページサイズが混在するPDF）では、期待どおりに動作しない場合があります。
- 本家 SumatraPDF と同等の動作保証はありません。

## ビルドについて

- 本機能を含む実行ファイルをビルドする場合は、**本ブランチ（`kz_3.5.2_patch_feature`）をチェックアウトして**ビルドしてください。
- Visual Studio 2026でビルドできることを確認しています。

## ライセンス

GNU General Public License v3.0
（詳細は同梱の `COPYING` ファイルを参照してください）

## アップストリーム

本ブランチのベースとなっている派生元リポジトリ：
- [https://github.com/dnobori/DN-fork-sumatrapdf/tree/dn_3.5.2_patch2](https://github.com/dnobori/DN-fork-sumatrapdf/tree/dn_3.5.2_patch2)

## 免責事項

- 本ブランチおよび本機能は 非公式の個人改変版です。
- SumatraPDF 本家とは無関係であり、動作保証はありません。
- 本改修は主に AI の支援を受けて行っているため、不具合等が含まれる可能性があります。

# 本家

[![Build](https://github.com/sumatrapdfreader/sumatrapdf/actions/workflows/build.yml/badge.svg?branch=master)](https://github.com/sumatrapdfreader/sumatrapdf/actions/workflows/build.yml)
## SumatraPDF Reader

SumatraPDF is a multi-format (PDF, EPUB, MOBI, CBZ, CBR, FB2, CHM, XPS, DjVu) reader
for Windows under (A)GPLv3 license, with some code under BSD license (see
AUTHORS).

More information:
* [website](https://www.sumatrapdfreader.org/free-pdf-reader)
* [manual](https://www.sumatrapdfreader.org/manual)
* [developer information](https://www.sumatrapdfreader.org/docs/Contribute-to-SumatraPDF)
