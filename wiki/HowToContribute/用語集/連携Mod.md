tModLoaderにおける有名なMODとして、

- Census - Town NPC Checklist
- Boss Checklist

の二つがあります。上記のMODは他MODにおいても対応率が非常に高く、新規の翻訳をする上でこの上記MODに関連した部分も対応する機会があるでしょう。

以下にMODのURL、MOD翻訳の一部抜粋、簡易的な用語集をまとめていきます。

## Boss Checklist

| 英文                     | 和文                                                   |
| ------------------------ | ------------------------------------------------------ |
|                          | ～で出現する(ボス召喚条件の主な末文。)                 |
|                          | ～を開始する(パンプキンムーンなどのイベント系)         |
| use ○○○ (, ...)          | ○○○を使う(使うか、...)                                 |
| Lasts until sunrise      | 日の出まで持続する。(パンプキンムーンなどのイベント系) |
| Spawn conditions unknown | このボスの召喚条件は不明です                           |

```hjson
BossSpawnInfo: {
  TorchGod: 地下に101本の松明を置く。101本目の松明が置かれるとイベントが始まる。
  MartianSaucer: 「火星人の狂気」中に時折現れる！「火星人の狂気」は、火星人の探査機に探知され、逃走を許すと始まる。
  DD2DarkMageT3: イベント「Old One's Army」のwave 5 (Tier 1)とWave 5 と Wave 6 (Tier 3)に出現する！[i:3816]と[i:3828]でOld One's Armyを開始する。
  DD2OgreT3: イベント「Old One's Army」のWave 7 (Tier 2)とWave 4 と Wave 6 (Tier 3)に出現する！[i:3816]と[i:3828]でOld One's Armyを開始する。
  PirateShip: 海賊の襲来中に時々出現する！[i:1315]で海賊の襲来を開始する。
  Everscream: フロストムーンのWave 4から出現する。[i:1958]でフロストムーンを開始する。
  SantaNK1: フロストムーンのWave 7から出現する。[i:1958]でフロストムーンを開始する。
  IceQueen: フロストムーンのWave 11から出現する。[i:1958]でフロストムーンを開始する。
  MourningWood: パンプキンムーンのWave 4から出現する。[i:1844]でパンプキンムーンを開始する。
  ・
  ・
  ・
  QueenSlimeBoss: "[i:4988]を聖域で使う。[i:4988]は地下聖域でパールストーンかピンクアイスのブロックに生える。"
  WallofFlesh: ガイドが生きているときに地獄の溶岩に[i:267]を投げ込むと出現する（投げ込んだ際にガイドは死亡する）[c/FF0000:討伐するとハードモードが始まります！]
  Deerclops: "[i:5120]を雪原で使う。もしくは夜中に吹雪の雪原に自然出現する"
  Skeletron: 夜のダンジョンを訪れ、老人と会話して「呪い（Curse）」を選ぶ、または夜に仕立て屋を[i:1307]などを用いて殺す
  QueenBee: "[i:1133]を使うか、ジャングルの蜂の巣で幼虫を見つけて壊す"
  BrainofCthulhu: "[i:1331]を使うか、真紅の大地でクリムゾンハートを３つ壊すたびに出現する"
  EaterofWorlds: "[i:70]を使うか、不浄の大地でシャドウオーブを３つ壊すたびに出現する"
  EyeofCthulhu: "[i:43]を夜に使う、または誰か1人のライフが200以上であれば、夜になるたびに1/3の確率で出現する（勝利後は発生しなくなる）"
  KingSlime: "[i:560]を使うか、マップの外側３分の１より外にランダムで出現する、もしくはスライムレイン中に１５０体のスライムを倒す"
  Unknown: このボスの召喚条件は不明です
}
```

## Town NPC Checklist

| 英文                                          | 和文                               |
| --------------------------------------------- | ---------------------------------- |
| When ○○○ has been defeated.                   | ○○○を撃破後                        |
| Acquire △△ other townspeople                  | 町に△△人の住民がいる時             |
| Find in the ○○○                               | ○○○で発見                          |
| Have an ○○○ in your inventory                 | インベントリに○○○を所持            |
| Always available, spawned on world generation | 常に出現可能(ワールド生成時に出現) |
| Use ○○○                                       | ○○○を使用                          |
| Conditions unknown                            | 条件不明                           |

```hjson
SpawnConditions: {
 TownSlimeCopper: スライムを銅の兜 [i:CopperHelmet]か銅の短剣 [i:CopperShortsword]に触れさせる
 TownSlimeYellow: ジャングルで魔法使いカエルに浄化の粉 [i:PurificationPowder]を使用
 TownSlimeRed: ブラッドムーン中に釣り上げる
 TownSlimeRainbow: 煌めくスライムの風船 [i:GelBalloon]をシマーに落とす
 TownSlimePurple: 宇宙層で不器用な風船スライムの風船を攻撃して割る
 TownSlimeOld: スケルトロンを倒した後、洞窟層の古びた揺れる宝箱に黄金の鍵 [i:GoldenKey]を使って解錠
 TownSlimeGreen: 自然発生するパーティーの時
 TownSlimeBlue: キングスライムを倒した後
 TownBunny: 動物学者から購入できるウサギライセンス [i:LicenseBunny]を使用
 TownDog: 動物学者から購入できるイヌライセンス [i:LicenseDog]を使用
 TownCat: 動物学者から購入できるネコライセンス [i:LicenseCat]を使用
 Princess: 町に全ての住民がいる時
 SantaClaus: フロストレギオンを撃退した後、12月15日から31日までの間のみ
 Cyborg: プランテラを倒した後
 Steampunker: メカニカルボスを倒した後
 Pirate: 海賊襲撃を撃退した後
 Truffle: ハードモードで、地上のキノコバイオームに家を建てる
 TaxCollector: ハードモードで、地底世界で苛まれた霊に浄化の粉 [i:PurificationPowder]を使用
 Wizard: ハードモードの地下層で発見
　　・
　　・
　　・
}
```
