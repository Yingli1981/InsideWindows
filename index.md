# インサイドWindows独習記録

## はじめに
Windowsプログラム設計・製作に必要な知識を習得するため

「インサイドWindows 第7版 上」という書籍を購入。 (※下巻は 2019/8/26現在未出版 (英語版も))

知識の整理・復習を兼ねて、独習で学んだことを本Wikiに記録する。
 
**購入書籍**

[インサイドWindows 第7版 上](https://www.amazon.co.jp/dp/4822253570)


## 用語集

>参考
>[OS基礎の基礎をまとめてみた。](https://qiita.com/tatsuya4150/items/f830c9b2ae33275aef42)


#OSの構成

ブートローダー

    ・コンピュータを起動したときによびだされて(boot)、OSとかを動かす仕事(load)をしているプログラムのこと。

カーネル

    ・OSの中核部分として頑張っているソフトウェア
    
        プロセス管理
    
        空間管理
    
        時間管理
    
        割り込み処理
    
        ファイルシステム
    
        ネットワーク

デーモン　(Windows OSでは”サービス")
    
        ・メモリ上で待機している常駐プログラムのUNIX系OSにおける呼び名

シェル

        ・人間からの入力をコンピュータに伝えるプログラム (「コマンドプロンプト」や「ターミナル」)

デスクトップ環境


アプリケーション



## 第1章 概念とツール
 
**Windowsのバージョン確認方法**

    ・コマンドプロンプトで「winver」実行 (ビルド番号もこれでわかる)
 
**OneCore**

    ・Win10 と モバイル用OS、ゲーム用OSなどとのカーネル統合
    
> 参考
>[ Windows 10 IPの開発が遅れる要因「OneCore」とは?](https://news.mynavi.jp/article/20160201-windows10report/)
 
**Win32API**

    ・Windows OSファミリーのユーザモードシステムのプログラミングインターフェース

        … なぜ "32"がつくのか…　昔の Windows 16ビット版と区別するため
 
    ・今は64ビットOSがあるので Windows API と呼ぶ
    
**Windows APIの種類**

    ・COM,  OLE
   
<!-- 
第2章 システムアーキテクチャ
第3章 プロセスとジョブ
第4章 スレッド
第5章 メモリ管理
第6章 I/Oシステム
第7章 セキュリティ



### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Yingli1981/InsideWindows/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

-->
