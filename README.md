# コーディング課題 2

書籍を検索するフロントエンド・アプリケーションを実装してください。

## 概要

[Google Books APIs](https://developers.google.com/books?hl=ja) を使用して、
[Google ブックス](https://books.google.co.jp/) のような、書籍を検索し、
検索結果を最大 10 件、表示するフロントエンド・アプリケーションを実装し、
Docker Compose を使用して、ローカル環境で実行可能な環境を構築してください。

[Google ブックス](https://books.google.co.jp/) のように、ページネーション、書籍名
や著者をクリックすると、詳細が表示される必要はありません。書籍情報としては、以下の情報を
含むようにしてください。

| 説明 | プロパティ名 |
| ----| ----------- |
| タイトル | volumeInfo.title |
| サブタイトル (あれば) | volumeInfo.subtitle |
| 著者 | volumeInfo.authors[] |
| 出版社 | volumeInfo.publisher |
| 発売日 | volumeInfo.publishedDate |
| サムネイル画像 | volumeInfo.imageLinks.thumbnail |

## 補足

要求どおり動作するだけでなく、単体テストも実装し、内部品質の高いコードを心がけてください。
内部品質については、以下の t_wada さんのスライドも参考にしてください。

- [質とスピード](https://speakerdeck.com/twada/quality-and-speed)

完了しましたら、成果物の GitHub のリポジトリの URL を提出してください。
