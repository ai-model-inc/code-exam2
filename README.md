# コーディング課題 2

書籍を検索するフロントエンド・アプリケーションを実装してください。

## 概要

この試験では与えられたAPIを使用して書籍を検索し結果を表示するWebアプリケーションを実装していただきます。

## 実装要件

- [Google Books APIs](https://developers.google.com/books?hl=ja) を使用して、[Google ブックス](https://books.google.co.jp/) のような、書籍を検索し、検索結果を最大 10 件表示できること。
- Docker Compose を使用して、ローカル環境で実行可能な環境を構築すること。
- 単体テストを実装すること。
- 書籍情報として、以下の情報を含むようにすること。

| 説明 | プロパティ名 |
| ----| ----------- |
| タイトル | volumeInfo.title |
| サブタイトル (あれば) | volumeInfo.subtitle |
| 著者 | volumeInfo.authors[] |
| 出版社 | volumeInfo.publisher |
| 発売日 | volumeInfo.publishedDate |
| サムネイル画像 | volumeInfo.imageLinks.thumbnail |


## 技術要件

以下の技術を満たすように実装してください。

- React.js
- TypeScript
- 関数コンポーネント
- React Hooks
- ES6+ の記法

## 補足

- UIデザインは提供されません。自由にデザインしてください。
- [Google ブックス](https://books.google.co.jp/) のように、ページネーション、書籍名や著者をクリックすると、詳細が表示される必要はありません。
- 要求どおり動作するだけでなく、単体テストも実装し、内部品質の高いコードを心がけてください。
- 内部品質については、以下の t_wada さんのスライドも参考にしてください。
  - [質とスピード](https://speakerdeck.com/twada/quality-and-speed)

完了しましたら、成果物の GitHub のリポジトリの URL を提出してください。
