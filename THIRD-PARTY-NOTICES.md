# 第三者ソフトウェアについて

ImgViewerのWebP読み込みには、Google / WebM Projectの **libwebp 1.6.0** と、公式上流の修正を使用しています。画像のデコードに必要な部分を実行ファイルに組み込んでいます。

- [libwebpのライセンス全文](LIBWEBP-LICENSE.txt)
- [追加の特許許諾](LIBWEBP-PATENTS.txt)
- [使用版と適用した修正の出典](LIBWEBP-PATCHES.txt)
- [libwebp公式リポジトリ](https://github.com/webmproject/libwebp)

これらの条件は、ImgViewer本体の [利用条件](LICENSE.txt) とは別に適用されます。

PNGの読み込みにはWindows Imaging Component、JPEG・GIFの読み込みにはGDI+を使用しています。これらはWindows標準の機能です。

Microsoft C/C++ランタイムの一部を実行ファイルに組み込んでいます。該当部分の利用条件は [LICENSE.txt](LICENSE.txt) に記載しています。
