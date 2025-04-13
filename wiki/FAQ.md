# よくある質問（FAQ）

## 目次
- [インストール・導入関連](#インストール導入関連)
- [日本語化・翻訳関連](#日本語化翻訳関連)
- [Mod・TML関連](#modtml関連)
- [トラブル・エラー対応](#トラブルエラー対応)
- [その他の質問](#その他の質問)

---

## インストール・導入関連

### Q. External localizerを導入したんだけど日本語化されない！
A.勘違いされがちですが、このModは「hjsonファイルを書き出し、読み込み」を行うためのModです。単に日本語化したいだけの場合は、External localizerとJapanesePackを導入してください。

### Q. 1.4.4対応？
A. はい、対応しています。

### Q. External localizer Beta はどこにある？
A. [こちらのページ](https://steamcommunity.com/sharedfiles/filedetails/?id=3401926459)からダウンロードできます。
Japanese Packが正式版対応したので何か事情がある人以外はおすすめしません。

### Q. フォルダに入れたのに反映されないんだけど？
A. 配置場所が間違っている、またはファイル名が誤っている可能性があります。
また、Terrariaのインストール先がOneDriveになっていたり、Steamクラウドがオンの場合、うまく反映されない時があります。

### Q. アスタリスクになるんだけど
A. [TrJpMod](https://steamcommunity.com/sharedfiles/filedetails/?id=3401926459)など、フォントが同梱されているリソースパックなどを導入してください。

### Q. いちいちファイル入れるのめんどいんだけど？
A. External localizerとExternal localizer JapanesePackを導入することで手間を省けます。

---

## 日本語化・翻訳関連

### Q. 翻訳したいんだけど、どうやって日本語化ファイルを作るの？
A. [翻訳のやり方](翻訳のやり方)を参考にしてください。

### Q. Japanese Packを導入するだけで日本語化できるModを教えて！
A. 対応Mod一覧は[こちら](https://github.com/ExternalLocalizer/TMLHonyaku/blob/main/TranslatedMods.csv)をご覧ください。

### Q. アイテムの原文表示とかはどうやるの？
A. 設定→Modの設定→External localizer→ローカライズの設定→ローカライズの項目の「アイテム名の表示形式」を変更すればできます。3つあるのでお好きなものを選んでください。
(このオプションをオンにしても適用されないModがいくつかあります)
ちなみに、TrJpMod(日本語化パック)を使用している場合、この方法だとバニラアイテムが「銅の短剣(銅の短剣)」のようになってしまうため、バニラアイテムの原文も見たい人はExternal localizer、External localizer JapanesePack、[TrJpMod[EN] (日本語化パック)](https://steamcommunity.com/sharedfiles/filedetails/?id=2865024243)をサブスクライブして使用してください。
原文だけ見たい方はフィルターのプリセットから原文表示したいものを個別でオンにしてください。

### Q. 誤訳見つけたよ！or ここ翻訳おかしくない？
A. 公式Discordで報告してください。改善にご協力いただけると助かります。
ただし、External Localizer公式以外が制作した翻訳はサポート対象外のため、ファイルの製作者にお問い合わせください。

### Q. 一部翻訳できてない箇所があるんだけど
A. 翻訳ファイルに漏れがある可能性があります。
どうしても気になる場合は[General Purpose Japanese Translation](https://steamcommunity.com/sharedfiles/filedetails/?id=3363076331)や[In-game Translate](https://steamcommunity.com/sharedfiles/filedetails/?id=3001536716)などのModを入れて対処してください。

### Q. アイテム名とかが翻訳されないんだけど
A. External localizerの設定をデフォルトにリセットしてみてください。

### Q. 一部のバニラアイテムとか、NPCのセリフが日本語化されないんだけど？
A. 仕様上訳せない箇所がいくつかあります。

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
以前にExternal localizerを導入していたことがある場合、古い設定ファイルが残っていて不具合を引き起こすことがあります。
以下の手順でフォルダ内の .hjson ファイルをすべて削除してください。

📁 該当フォルダ：ドキュメント/My Games/Terraria/tModLoader/ExternalLocalizer/localization


それでもエラーが解消しない場合、Modのアップデートが正常に反映されていないことがあります。
一度「サブスクライブ解除 → 再度サブスクライブ」をお試しください。
改善しない場合は、一度該当Modファイルをすべて削除し、再導入してみてください。

📁 Calamity Modのワークショップファイルの場所：Steam/steamapps/workshop/content/1281930/2824688072


💬 解決しない場合は…

それでも問題が解消しない場合は、コメント欄またはDiscordにてお問い合わせください。
（※なお、tModLoaderのエラーメッセージはかなり曖昧な場合があります）

### Q. 文字がウィンドウからはみ出たり、重なって押せなかったりするんだけど
A. 日本語フォントの幅やレイアウトの都合で表示が崩れる場合があります。
翻訳ファイルは基本的に[TrJpMod](https://steamcommunity.com/sharedfiles/filedetails/?id=3401926459)のフォントを基準として作られています。

### Q. ゲーム内ワークショップから検索しても出てこないんだけど
A. [Steamワークショップ](https://steamcommunity.com/sharedfiles/filedetails/?id=2986383249)からダウンロードすることを推奨します。

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
A. SteamでModを購読（インストール）する機能のことです。
