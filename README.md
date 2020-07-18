# myAssembler
ScalaによるRISC-Vのアセンブリを機械語にアセンブルするアセンブラ

## 概要
RV32Iのアセンブリを機械語に翻訳するプログラム。
詳しい説明は[こちら](https://qiita.com/a163236/items/1ea950f743457ede5d0b)(私のqiitaサイト)の方が分かりやすいです。
未実装の命令がいくつかあります。未完成です、なにかあれば教えてください。

## 始め方
このリポジトリをダウンロードして、IntelliJ IDEAでこのフォルダを開くと使えます。

## 使い方
Assembly.txtに実行したいAssemblyを書く
/src/main/scala/Assembler/Assemblerが実行ファイルなのでこれを実行する。

すると、Assembly.txtに書いていたアセンブリがコンソールに出力される。

## 連絡先
[@a163236](https://twitter.com/a163236)まで