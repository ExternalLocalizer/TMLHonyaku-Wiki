
## 目次
- [インストール・導入関連](#インストール導入関連)
- [日本語化・翻訳関連](#日本語化翻訳関連)
- [Mod・TML関連](#modtml関連)
- [トラブル・エラー対応](#トラブルエラー対応)
- [その他の質問](#その他の質問)

---

## インストール・導入関連

### Q. External localizerを導入したんだけど日本語化されない！
A.勘違いされがちですが、このModは「hjsonファイルを書き出し、読み込み」を行うためのModです。単に日本語化したいだけの場合は、[External localizer](https://steamcommunity.com/sharedfiles/filedetails/?id=2986383249)と[External localizer JapanesePack](https://steamcommunity.com/sharedfiles/filedetails/?id=3401890281)を導入してください。

### Q. 1.4.4対応？
A. はい、対応しています。

### Q. External localizer Beta はどこにある？
A. [こちらのページ](https://steamcommunity.com/sharedfiles/filedetails/?id=3401926459)からダウンロードできます。
Japanese Packが正式版対応したので何か事情がある人以外はおすすめしません。

### Q. フォルダに入れたのに反映されないんだけど？
A. 配置場所が間違っている、またはファイル名が誤っている可能性があります。
また、Terrariaのインストール先がOneDriveになっていたり、Steamクラウドがオンの場合、うまく反映されない時があります。

### Q. アスタリスクになるんだけど
A. [TrJpMod](https://steamcommunity.com/sharedfiles/filedetails/?id=2865024243)など、フォントが同梱されているリソースパックなどを導入してください。

### Q. いちいちファイル入れるのめんどいんだけど？
A. External localizerとExternal localizer JapanesePackを導入することで手間を省けます。

---

## 日本語化・翻訳関連

### Q. 翻訳したいんだけど、どうやって日本語化ファイルを作るの？
A. [翻訳のやり方](翻訳のやり方)を参考にしてください。

### Q. Japanese Packを導入するだけで日本語化できるModを教えて！
A. 対応Mod一覧は[こちら](https://github.com/ExternalLocalizer/TMLHonyaku/blob/main/TranslatedMods.csv)をご覧ください。

### Q. アイテム名の原文表示を消したい/表示させたい、変更はどうやるの？
A. 設定→Modの設定→External localizer→ローカライズの設定→ローカライズの項目の「アイテム名の表示形式」を変更すればできます。3つあるのでお好きなものを選んでください。
(このオプションをオンにしても適用されないModがいくつかあります)  
原文のみ表示させたい方はフィルターのプリセットから原文表示したいものを個別でオンにしてください。

### Q. 原文表示をオンにしているのに、バニラアイテム名が日本語で二重に表示されるのはなぜ？
A.TrJpの固有名詞日本語版を使っているのが原因です。
バニラアイテムの原文も見たい人はTrJpModを無効化し、[TrJpMod[EN] (日本語化パック)](https://steamcommunity.com/sharedfiles/filedetails/?id=2865024243)をサブスクライブして使用してください。

### Q. 誤訳見つけたよ！or ここ翻訳おかしくない？
A. 公式Discordで報告してください。改善にご協力いただけると助かります。
ただし、External Localizer公式以外が制作した翻訳はサポート対象外のため、ファイルの製作者にお問い合わせください。

### Q. 一部のアイテム名やNPCセリフなどが翻訳されないのはなぜ？  
A. 翻訳されない理由は主に2つあります。
**翻訳漏れ:翻訳データが未更新のため表示が原文のままになる場合**  
こちらはアイテム名とTooltipが全て未翻訳の場合に多いです。原因としてはアップデートで追加された箇所のため対応が追いついていないなどが考えられます。公式Discordでフィードバックをお送りください。  
**仕様上の制限:ゲームの仕様により翻訳を適用できない部分がある場合** 
こちらはNPCのセリフや、Modにより効果が改変されたアイテムなどに多いです。現状こちら側では対応できません。  
また、設定によって未翻訳状態になることもあります。気になる場合は、External localizerの設定をデフォルトにリセットしたり、
[In-game Translate](https://steamcommunity.com/sharedfiles/filedetails/?id=3001536716)などの補助翻訳Modを導入して対処してください。

---

## Mod・TML関連

### Q. TMLをダウンロードする際の注意点は？
A. 安定版を使用すること、公式サイトか[Steam経由](https://store.steampowered.com/app/1281930/tModLoader/)でインストールすることを推奨します。
また、Terrariaのインストール先がOneDriveになっていたり、Steamクラウドがオンの場合、不具合の原因になります。

### Q. 対応Modは？
A. [こちら](https://github.com/ExternalLocalizer/TMLHonyaku/blob/main/TranslatedMods.csv)にリストがあります。

### Q. Modアップデートしたらエラー吐くようになっちゃったんだけど？
A. 日本語化ファイルとModのバージョンが一致していない可能性があります。アップデート対応をお待ちください。

### Q. Mod入れたらデータ壊れたんだが？
A. 万が一に備えてバックアップを取ってからModを導入することを推奨します。

---

## トラブル・エラー対応

### Q. (バージョンが違うって)エラー吐くんだが？
A. 現在、Calamity Modなど大規模Modが最新版に対応していないということは、**ほぼありません**。
以前にExternal localizerを導入していたことがある場合、古い日本語化ファイルが残っていて不具合を引き起こすことがあります。
以下の手順でフォルダ内の .hjson ファイルをすべて削除してください。

**該当フォルダ：**
ドキュメント/My Games/Terraria/tModLoader/ExternalLocalizer/localization


それでもエラーが解消しない場合、Modのアップデートが正常に反映されていないことがあります。
一度「サブスクライブ解除 → 再度サブスクライブ」をお試しください。
改善しない場合は、一度該当Modファイルをすべて削除し、再導入してみてください。

**Calamity Modのワークショップファイルの場所：**
Steam/steamapps/workshop/content/1281930/2824688072

それでも問題が解消しない場合は、コメント欄またはDiscordにてお問い合わせください。
（※なお、tModLoaderのエラーメッセージはかなり曖昧な場合があります）

### Q. 文字がウィンドウからはみ出たり、重なって押せなかったりするんだけど
A. 日本語フォントの幅やレイアウトの都合で表示が崩れる場合があります。
翻訳ファイルは基本的に[TrJpMod](https://steamcommunity.com/sharedfiles/filedetails/?id=2864004486)のフォントを基準として作られています。

### Q. ゲーム内ワークショップから検索しても出てこないんだけど
A. [Steamワークショップ](https://steamcommunity.com/sharedfiles/filedetails/?id=2986383249)からダウンロードすることを推奨します。

### Q. サブスクライブしたのに使用できない！なんで？   
tmodloaderのアップデートとサブスクライブのタイミングが重なったり、ダウンロードが正常に完了しなかった場合に発生することがあります。  
PCの再起動や、Steamクライアントを完全に終了させた上で、一度サブスクライブを解除し、再度サブスクライブすると改善する場合があります。  
また、tmodloaderのバージョンが最新のものになっているかを確認してください。  
**Steamライブラリ→tmodloader→管理(歯車マーク)→プロパティ→ベータ→ベータへの参加→なし に変更**

---

## その他の質問

### Q. Steam WorkShopって危険ですか？
A. 基本的には安全ですが、評価や作者を確認してから導入するようにしてください。

### Q. Githubって危険ですか？
A. External Localizerのものであれば基本的に安全ですが、自己責任で導入してください。

### Q. スマホでもできますか？
A. モバイル版では基本的に日本語化Modは使用できません。

### Q. 対応OSは？
A. Windowsが主に対象ですが、Mac(Intel)/Linux(Arch)でも動作する場合があります。

### Q. サブスクライブって何？
A. SteamでModを購読（インストール）する機能のことです（無料）。
