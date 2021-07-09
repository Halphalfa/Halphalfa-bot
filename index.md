## Halphalfa-bot とは何ですか？

- [Discord](https://discord.com/) 用の [BOT](https://it-trend.jp/words/bot) です。

もとは SHIP01 で活動中のチーム [Halphalfa(web)](https://seesaawiki.jp/halphalfa/) [(Twitter)](https://twitter.com/halphalfa_ngs) の外部チャットツールとして利用した Discord のチームメンバー専用のサーバー向けに開発していましたが、一部機能を一般公開しチーム外の方にもご利用頂けるように調整したものです。

### 一般公開中の主な機能

- 〘NEW! 2021/07/10〙[PSO2NGS公式/NEWS](https://pso2.jp/players/news/) の最新記事が追加されるとDiscordの「#公式情報」チャンネルへ見出しとリンクを提供する機能。
- 〘SINCE 2021/07/08〙[@RappyBurst](https://twitter.com/RappyBurst/) さんの発信するアルファーリアクター情報をDiscordの「#αリアクター」チャンネルへリンク提供する機能。
- 〘DEPRECATED 2021/07/10〙[@Mr_Rappy](https://twitter.com/Mr_Rappy/) さんの整理された雷雨予報データを基に…
  - 「#雷雨botちゃん」チャンネルへ雷雨のN分前に雷雨予報のお知らせを提供する機能。
  - オンライン中のステータス表示部分で簡易的に次回の雷雨予報のお知らせを提供する機能。
  - (2021/07/10 追記) この機能は公式の対応状況リスト[【ギガンティクス出現期間およびエネミーのHP変化に関する調整について】](https://pso2.jp/players/support/bugfixes/i_measures_20210709_1/)のなかで「天候の変化が完全にランダムな発生になっていない不具合」との表現で現状の方法による雷雨の予報は不具合としての副産物と考えられる見解を表しました。このため本機能は暫定的にDEPRECATED(非推奨)の機能とします。公式の天候関連の修正に併せて本機能はOBSOLETED(廃止)とします。

![参考画像3](./hal-bot-3.png)

### 使い方: Discord サーバーへ Halphalfa-bot を導入する方法

1. Halphalfa-bot を導入したいサーバーをDiscordで作成/準備して下さい。
2. Halphalfa-bot の招待リンク <https://discord.com/api/oauth2/authorize?client_id=860116387631595530&permissions=2048&scope=bot> へウェブブラウザーでアクセスし、 Halphalfa-bot を入れてあげて下さい。

### 使い方: 「#公式情報」チャンネル

- Halphalfa-bot が書き込み可能な「#公式情報」チャンネルを作成するだけで動作します。

![参考画像4](./hal-bot-4.png)

### 使い方: 「#αリアクター」チャンネル

- Halphalfa-bot が書き込み可能な「#αリアクター」チャンネルを作成するだけで動作します。

![参考画像1](./hal-bot-1.png)

### 使い方: 「#雷雨botちゃん」チャンネル

- Halphalfa-bot が書き込み可能な「#雷雨botちゃん」チャンネルを作成するだけで動作します。(雷雨の1分前に向こう3件分の予報が投稿されます)
- 「#雷雨botちゃん10」のようにチャンネル名の終わりに`2`から`30`までの数字を付けたチャンネルを用意するとその数字の分数だけ前に予報が投稿されます。
  - 例: 「#雷雨botちゃん10」なら10分前、「#雷雨botちゃん5」なら5分前に予報が届きます。

![参考画像1](./hal-bot-2.png)

## 利用規約

以下のすべての条項を満たす、または同意頂ける場合は個人、チームを問わず Halphalfa-bot の利用を許諾します。

1. PSO2NGS の現役プレイヤー個人または現役で活動中のチームでの利用であること。
2. ゲーム内または関連したSNSアカウント等で公序良俗に反する、または他人を著しく傷付けるような、あるいは乱暴な発言や行動をとらない事を心がけている善良なプレイヤーまたはそれを好しとするチームであること。
4. 雷雨データの整理や報告、アルファーリアクターの探索や情報整理を行ってくれる有志のプレイヤーをリスペクトできるプレイヤーまたはチームであること。
5. 著者またはその所属チームの都合により緊急メンテナンス等ご利用頂けない期間がありえることに同意頂ける方、またそのような事態にクレームを投げつけて来ない優しい方。
6. 不具合、過負荷、機器や利用サービスの事故、データの誤り等により想定外の何かが起きてしまっても水に流してできるだけポジティブに未来志向でお付き合い頂ける方。

## 謝辞

- Twitter
  - 🙏 [@RappyBurst](https://twitter.com/RappyBurst/) さんはじめアルファーリアクターの情報流通に大きく貢献されている全ての方に感謝いたします。
  - 🙏 [@Mr_Rappy](https://twitter.com/Mr_Rappy/) さんはじめ雷雨の観測と予報の情報流通に大きく貢献されている全ての方に感謝いたします。
- オンラインサービス
  - 🙏 [Replit](https://replit.com/) BOT の開発と配置に利用させて頂いております。ありがとうございます。
  - 🙏 [UptimeRobot](https://uptimerobot.com/) BOT の死活監視に利用させて頂いております。ありがとうございます。
  - 🙏 [Discord](https://discord.com/) チームの外部チャットツールとしてたいへん有益に利用させて頂いております。ありがとうございます。
  - 🙏 [Twitter](https://twitter.com/) 公開ツイートを容易に扱える Web API を利用させて頂いております。ありがとうございます。
- PSO2NGS
  - 🙏 [SEGA](https://sega.jp/) すばらしい作品を世に出して頂きありがとうございます。どうか不具合に押しつぶされず頑張って下さい💪
- Wikimedia commons
  - 🙏 [File:Ruhland, verlängerte Grenzstr. Höhe Fichtestr. 4-5, Blaue Luzerne am Wegrand, Blüten, Spätfrühling, 01.jpg](https://commons.wikimedia.org/wiki/File:Ruhland,_verl%C3%A4ngerte_Grenzstr._H%C3%B6he_Fichtestr._4-5,_Blaue_Luzerne_am_Wegrand,_Bl%C3%BCten,_Sp%C3%A4tfr%C3%BChling,_01.jpg) Halphalfa-bot ちゃんの最初のアイコン画像として"道端のアルファルファの花の写真"(CC)を使用させて頂きました。可愛らしい花の写真の Wikimedia commons での公開に感謝いたします。

皆様いつも大変ありがとうございます。今後ともお互いに PSO2NGS を楽しみ続けられれば嬉しく思います。🙏

## 著者

- [L,A.M.](https://twitter.com/LAM35105379) @ SHIP01(JP) / PSO2NGS チーム [Halphalfa(web)](https://seesaawiki.jp/halphalfa/), [(Twitter)](https://twitter.com/halphalfa_ngs)
