## What is OmegaSisters/Homepage?

### Background

「第１回おめシスのホームページをプルリクだけで更新していったらどうなるの？」という、おめがシスターズの企画です。

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">おめシスのホームページをGithubのプルリクで更新していったらどうなるのか、こっそり検証中です。そのうち動画にします！<a href="https://t.co/rErhv32NNR">https://t.co/rErhv32NNR</a></p>&mdash; おめがレイ@バーチャル双子YouTuber (@omesis_ray) <a href="https://twitter.com/omesis_ray/status/1209057136992387072?ref_src=twsrc%5Etfw">December 23, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

## How to contribute?

There are endless possibilities for users to think about, but there are three main ways.

- Issue / Comment
- Throw and review PR
- Share on Twitter 👍

## Getting Started

yarn, npm の場合それぞれ書いています

### ローカルプレビュー (Node.js)

#### yarn

```
yarn start
```

#### npm

```
npm run start
```

http://localhost:8080 にホストされます。

### コード整形(Node.js 環境必須)

#### yarn

```
yarn format
```

#### npm

```
npm run format
```

### Push する前にすること

ソースコードを編集した後、Push する前にビルドを行ってください

#### yarn

```
yarn build
```

#### npm

```
npm run build
```

### テストコードを実行する (Node.js)

`__tests__`, `preact` にサンプルテストケースがあります。

#### yarn

```
yarn test
```

#### npm

```
npm run test
```

### 使用されている技術にはどんなものがありますか？

[こちら](./documents/environment/README.md)を確認してください。
