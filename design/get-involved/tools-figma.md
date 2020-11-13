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
To join the WordPress.org Figma team, ping in [#design](https://make.wordpress.org/design/tag/design/) on chat.wordpress.org and let us know whether you need view-only or edit access. A Figma admin will contact you for your email address to set up your account.
-->
WordPress.org の Figma チームに参加するには、chat.wordpress.org の [#design](https://make.wordpress.org/design/tag/design/) に ping を入力して、表示のみの権限でのアクセスか編集権限でのアクセスかを知らせてください。Figma の管理者があなたのメールアドレスを連絡して、アカウントを設定します。

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

### Files

#### Set a Custom Thumbnail (Cover)

[![](https://i1.wp.com/make.wordpress.org/design/files/2020/04/figma-covers.png?fit=776%2C371&ssl=1)](https://i1.wp.com/make.wordpress.org/design/files/2020/04/figma-covers.png?ssl=1)

How to add a cover to your Figma file:

1.  Create a new page in your document and call it “Cover”. Make sure it’s the first page in your document.
2.  From the Assets panel, search for figma-cover. You may need to enable the Utilities library for it to show up.
3.  Select the cover that’s appropriate for the status of your project and drag it anywhere in your Cover page.
4.  Frame the selection to create a frame around the cover. For consistency, you may want to rename this “Cover”.
5.  Click anywhere outside the frame to deselect. Change the background of your screen to match the cover.

Cover color codes:

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

#### Versioning

*   Keep titles to 25 characters or less.
*   Keep your description to 140 characters or less.
*   Use the imperative mood for the title.
*   Use the description to explain ‘what’ and ‘why’ versus ‘how’.

### Pages

You can use Pages to:

*   Iterate on different versions of a concept or idea
*   Break up designs by platform or device
*   Arrange Components and Styles into categories
*   Track each stage of the design process
*   Create different Prototyping flows for the same designs

Organize your pages:

1.  Cover: always at the top, to use it as a thumbnail preview.
2.  Iterations: keep the latest at the top organized in descending order.
3.  Current UI: take some screenshots to document how the UI was before working on it. This is extremely valuable to keep track of the evolution of the product, to tell the story in design reviews.
4.  Explorations: for testing different approaches/design patterns including discarded design

## Team Library

You can use the Team Library to access these resources across WordPress.org Team Files and Projects. This allows you to maintain a consistent brand and style, at scale.

This is a shared Figma library, which means its components are used by others. Please don’t make changes unless you are contributing components (see “Contributing components”). For questions, see the feedback section at the bottom of this page.

[![](https://i1.wp.com/make.wordpress.org/design/files/2020/04/figma-library-structure.png?resize=776%2C377&ssl=1)](https://i1.wp.com/make.wordpress.org/design/files/2020/04/figma-library-structure.png?ssl=1)

### WordPress Foundation

→ The core elements that make up visual design across the project. These are design tokens (like variables, but for design!) and core styles that don’t change often once established.

*Colours, type styles, icons, spacers, etc.*

### WordPress Components

This library contains available Figma components that mirror the base UI components found in the [@wordpress/components](https://www.npmjs.com/package/@wordpress/components) npm package. They are stable, fully supported, and ready for use in projects. @wordpress/components is an npm package that is published via the [Gutenberg repo](https://github.com/WordPress/gutenberg).

*Component documentation:* [*https://developer.wordpress.org/block-editor/*](https://developer.wordpress.org/block-editor/)

### WordPress Patterns

→ Larger patterns made up of individual UI components combined.

Blocks, navigation bars, Gutenberg’s sidebar, etc.

### Utilities

Stores things like covers, sticky notes, and diagram and wireframing components

## Contribution Workflows

### Component Contribution

> [WordPress components](https://make.wordpress.org/design/handbook/get-involved/wordpress-components/)

## References

The Block Editor Handbook  
[https://developer.wordpress.org/block-editor/](https://developer.wordpress.org/block-editor/)

Block Support Documentation [https://wordpress.org/support/category/block-editor/](https://wordpress.org/support/category/block-editor/)
