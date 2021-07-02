<!--
# Tools: Figma
-->
# ツール: Figma

<!--
Familiarizing oneself with the Figma files in the WordPress.org account can be difficult. This document will provide a high-level overview of the Figma structure and help anyone become familiar with the files therein.
-->
WordPress.org アカウント内の Figma ファイルに慣れるのは難しいかもしれません。このドキュメントでは、Figma の構造についてハイレベルな概要を提供し、誰でもその中にあるファイルに慣れることができるようにします。

<!--
## Overview
-->
## 概要

<!--
[Figma](https://www.figma.com) allows you to design and prototype your WordPress experiences, together, in real-time and in one place.
-->
[Figma](https://www.figma.com) では、WordPress の体験を一か所で一緒にリアルタイムにデザインしたり、プロトタイプを作成したりすることができます。

<!--
Figma is built for the browser, so you can use it across any platform (Windows, Mac, Linux, and Chromebook). No downloads or updates required.
-->
Figma はブラウザ用に作られているので、どのプラットフォーム（Windows、Mac、Linux、Chromebook）でも使用できます。ダウンロードやアップデートは必要ありません。

<!--
For those that prefer the app experience, you can download the Figma Desktop App for Windows and Mac. Or use the Figma Mirror app to take your live presentations to the next level. Learn more and download the apps at [https://www.figma.com/downloads/](https://www.figma.com/downloads/)
-->
アプリでお使いになりたい方は、Windows および Mac 用の Figma デスクトップアプリをダウンロードしてください。また、Figma Mirror アプリを使用すると、ライブ・プレゼンテーションを次のレベルに引き上げることができます。詳細については、[https://www.figma.com/downloads/](https://www.figma.com/downloads/) でアプリをダウンロードしてください。

<!--
## Getting Started
-->
## はじめに

<!--
### How to get Figma access
-->
### Figmaにアクセスする方法

<!--
The [WordPress Figma library](https://www.figma.com/file/e4tLacmlPuZV47l7901FEs/WordPress-Design-Library?node-id=1%3A2) is publicly open and available for all to view. If you require edit access to contribute design work to a new or existing project, please ping in [#design](https://wordpress.slack.com/archives/C02S78ZAL) channel on the [Making WordPress Slack](https://chat.wordpress.org/).
-->
[WordPress Figma ライブラリ](https://www.figma.com/file/e4tLacmlPuZV47l7901FEs/WordPress-Design-Library?node-id=1%3A2)は公開されており、誰でも見ることができます。新規または既存のプロジェクトにデザインを提供するために編集権限が必要な場合は、[Making WordPress Slack](https://chat.wordpress.org/)の[#design](https://wordpress.slack.com/archives/C02S78ZAL)チャンネルに連絡してください。

<!--
### Learning Figma
-->
### Figmaを学ぶ

<!--
Once you’re signed in, you can check out the [Figma Help Center](https://help.figma.com/) for getting started tutorials and more.
-->
サインインをしたら、[Figma Help Center](https://help.figma.com/) をチェックして、チュートリアルを始めてみましょう。

<!--
## Structure
-->
## 構造

[![](https://i1.wp.com/make.wordpress.org/design/files/2020/04/home-screen.png?resize=776%2C437&ssl=1)](https://i1.wp.com/make.wordpress.org/design/files/2020/04/home-screen.png?ssl=1)

<!--
### Projects
-->
### Projects

<!--
You can use Projects to group Files in one place. Noted that It’s not possible to create subfolders within the Projects.
-->
Projects を使って、ファイルを一箇所にまとめることができます。注意点としては、Projects 内にサブフォルダを作成することはできません。

<!--
#### Project Naming
-->
#### プロジェクトの命名

<!--
Make sure you follow the general component guidelines and naming conventions.
-->
一般的なコンポーネントのガイドラインと命名規則に従ってください。

<!--
*   Use the sentence case with spaces.
-->
*   スペースのあるセンテンスケースを使用しましょう。

<!--
### Files
-->
### ファイル

<!--
#### Set a Custom Thumbnail (Cover)
-->
#### カスタムサムネイル（カバー）を設定する

[![](https://i1.wp.com/make.wordpress.org/design/files/2020/04/figma-covers.png?fit=776%2C371&ssl=1)](https://i1.wp.com/make.wordpress.org/design/files/2020/04/figma-covers.png?ssl=1)

<!--
How to add a cover to your Figma file:
-->
Figma ファイルにカバーを追加する方法:

<!--
1.  Create a new page in your document and call it “Cover”. Make sure it’s the first page in your document.
2.  From the Assets panel, search for figma-cover. You may need to enable the Utilities library for it to show up.
3.  Select the cover that’s appropriate for the status of your project and drag it anywhere in your Cover page.
4.  Frame the selection to create a frame around the cover. For consistency, you may want to rename this “Cover”.
5.  Click anywhere outside the frame to deselect. Change the background of your screen to match the cover.
-->
1. ドキュメントに新しいページを作成し、それを「Cover」と名付けます。それがドキュメントの最初のページであることを確認してください。
2. Assets パネルから、figma-cover を探します。それを使うために、Utilities library を有効にする必要があります。
3. プロジェクトの状態に適したカバーを選択し、Cover ページの任意の場所にドラッグします。
4. 選択範囲を枠で囲み、カバーの周りに枠（Frame）を作成します。一貫性を持たせるために、 この名前を「Cover」に変更するとよいでしょう。
5. 枠外の任意の場所をクリックして選択を解除します。画面の背景を表紙に合わせて変更します。

<!--
Cover color codes:
-->
カバーのカラーコード:

Status

Color code

Archived (do not use)

[#D94F4F](https://make.wordpress.org/design/tag/d94f4f/)

In design

[#F0B849](https://make.wordpress.org/design/tag/f0b849/)

In development

[#4AB866](https://make.wordpress.org/design/tag/4ab866/)

Shipped

[#00669B](https://make.wordpress.org/design/tag/00669b/)

Design resource/library

[#23282D](https://make.wordpress.org/design/tag/23282d/)

<!--
#### Versioning
-->
#### バージョニング

<!--
*   Keep titles to 25 characters or less.
*   Keep your description to 140 characters or less.
*   Use the imperative mood for the title.
*   Use the description to explain ‘what’ and ‘why’ versus ‘how’.
-->
*   タイトル（title）は25文字以下にします。
*   説明文（description）は140字以下にします。
*   タイトルには命令法を使ってください。
*   「何を」「なぜ」「どのように」説明するために説明文を使用します。

<!--
### Pages
-->
### ページ

<!--
You can use Pages to:
-->
Pages を使用して以下のことができます:

<!--
*   Iterate on different versions of a concept or idea
*   Break up designs by platform or device
*   Arrange Components and Styles into categories
*   Track each stage of the design process
*   Create different Prototyping flows for the same designs
-->
*   コンセプトやアイデアのさまざまなバージョンを繰り返す
*   プラットフォームまたはデバイスごとに設計を分割する
*   コンポーネントとスタイルをカテゴリに分類する
*   設計プロセスの各段階を追跡する
*   同じデザインに対して異なるプロトタイピングフローを作成する

<!--
Organize your pages:
-->
ページを整理する:

<!--
1.  Cover: always at the top, to use it as a thumbnail preview.
2.  Iterations: keep the latest at the top organized in descending order.
3.  Current UI: take some screenshots to document how the UI was before working on it. This is extremely valuable to keep track of the evolution of the product, to tell the story in design reviews.
4.  Explorations: for testing different approaches/design patterns including discarded design
-->
1.  Cover: サムネイルプレビューとして使用するために、常に上部に表示されます。
2.  イテレーション: 最新のものを先頭にして、降順に整理します。
3.  現在のUI: 作業前のUIがどのようになっていたかを記録するためにスクリーンショットを撮影します。これは、製品の進化を追跡し、デザインレビューでストーリーを伝えるために非常に貴重なものです。
4.  Explorations: さまざまなアプローチ/デザインパターンをテストするために、廃棄されたデザインも含みます。

<!--
## Team Library
-->
## チームライブラリ

<!--
You can use the Team Library to access these resources across WordPress.org Team Files and Projects. This allows you to maintain a consistent brand and style, at scale.
-->
チームライブラリを使って、WordPress.org のチームファイルやプロジェクト全体でこれらのリソースにアクセスすることができます。これにより、規模に応じて一貫したブランドとスタイルを維持することができます。

<!--
This is a shared Figma library, which means its components are used by others. Please don’t make changes unless you are contributing components (see “Contributing components”). For questions, see the feedback section at the bottom of this page.
-->
これは共有された Figma ライブラリであり、そのコンポーネントは他の人が使用することを意味します。コンポーネントに貢献している場合を除き、変更を加えないでください（「コンポーネントへの貢献」を参照してください）。質問は、このページの下部にあるフィードバック・セクションを参照してください。

[![](https://i1.wp.com/make.wordpress.org/design/files/2020/04/figma-library-structure.png?resize=776%2C377&ssl=1)](https://i1.wp.com/make.wordpress.org/design/files/2020/04/figma-library-structure.png?ssl=1)

<!--
### WordPress Design Library
-->
### WordPress　デザインライブラリ

<!--
The previous 3 libraries are now combined into one [single file](https://www.figma.com/file/e4tLacmlPuZV47l7901FEs/WordPress-Design-Library). This contains components, styles and icons.
-->
これまでの3つのライブラリを1つの[単一ファイル](https://www.figma.com/file/e4tLacmlPuZV47l7901FEs/WordPress-Design-Library)にまとめました。コンポーネント、スタイル、アイコンが含まれています。

<!--
## Contribution Workflows
-->
## 貢献のワークフロー

<!--
### Component Contribution
-->
### コンポーネントへの貢献

[https://make.wordpress.org/design/handbook/get-involved/wordpress-components/](https://make.wordpress.org/design/handbook/get-involved/wordpress-components/)

<!--
## References
-->
## 参考文献

<!--
The Block Editor Handbook
[https://developer.wordpress.org/block-editor/](https://developer.wordpress.org/block-editor/)
-->
ブロックエディターハンドブック
[https://ja.wordpress.org/team/handbook/block-editor/](https://ja.wordpress.org/team/handbook/block-editor/)

<!--
Block Support Documentation [https://wordpress.org/support/category/block-editor/](https://wordpress.org/support/category/block-editor/)
-->
ブロックサポートドキュメンテーション [https://wordpress.org/support/category/block-editor/](https://wordpress.org/support/category/block-editor/)
