# WordPress デザインハンドブック

こちらは [WordPress Design Handbooks](https://make.wordpress.org/design/handbook/) の翻訳用リポジトリです。

design ディレクトリ内にある英文を翻訳していきます。

ブラウザ上で翻訳したいmdファイルをクリックし、鉛筆マークの「Edit this file」をクリックすることでブラウザ上でも更新（プルリクエスト）できます。

翻訳の提案は、このデザインハンドブックでは **プルリクのみで OK** です。

担当してみたい箇所を一人で時間をかけて翻訳したいなどのご希望がありましたら、 [WordPress 日本語 Slack](http://bit.ly/join-wordslack) の design チャンネルまでご相談ください。

GitHub が初めての方も [翻訳開始から提案までの流れ](https://github.com/jawordpressorg/community-handbook/wiki/%E7%BF%BB%E8%A8%B3%E9%96%8B%E5%A7%8B%E3%81%8B%E3%82%89%E6%8F%90%E6%A1%88%E3%81%BE%E3%81%A7%E3%81%AE%E6%B5%81%E3%82%8C) を参考に、是非ご参加ください。

## 翻訳方法

__原文例：__

```
# Welcome
```

__手順：__

1.  __原文をコメントアウトします。__
    ```
    <!-- # Welcome -->
    ```
    _`<!--` の後ろと、`-->` の前には半角スペースを入れてください。翻訳の最小単位 (コメントアウトの単位) は段落 (空行から空行まで) でお願いします。_
2.  __コメントアウトした原文の下に翻訳を追加します。__
    ```
    <!-- # Welcome -->
    # ようこそ
    ```
3.  __`master` ブランチにプルリクエストします。__

## 翻訳用語集

翻訳に悩んだ場合はまず[翻訳用語集](https://github.com/jawordpressorg/community-handbook/blob/master/glossary.md)を参照してください。

## 原文更新方法

1.  [`en` ブランチ](https://github.com/jawordpressorg/community-handbook/tree/en)をチェックアウトします。
2.  原文を更新します。
3.  [`en` ブランチ](https://github.com/jawordpressorg/community-handbook/tree/en)にプルリクエストします。

_`en` ブランチには翻訳を含めないでください。_
