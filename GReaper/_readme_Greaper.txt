﻿このMODで追加されるもの
武術1種とその習得用のMA本と初期特性、職業
武器7種とその作成レシピ6種
レシピのうち2種が載った製作スキル本1種


■追加武術
・グリムリーパー
　大鎌・戦闘用大鎌およびこのMODで追加される各種大鎌装備時にのみ有効な武術です。
　鎌装備時のみ有効なパッシブが3種あり最初は1つですが近接戦闘レベルの上昇に伴い順次開放されます。
　その他詳しくはmartialarts.jsonとtechniques.jsonを参照のこと。arpenは指定属性の防御を数値分無視の効果です、多分。

■追加特性
・大鎌使い 3pt
　グリムリーパーを初期修得するための特性です。

■追加職業
・死神見習い 2pt
　追加武術用の職業特性を習得し、武器に戦闘用大鎌と関連スキルを少しずつ所持したスターターキット職です。
　服装は容積13の戦闘用大鎌を開幕ドロップしないように選びました。食人嗜好などで初期所持品が増えた場合その限りではありません。
　その他の生存に必要なアイテムの類は特に積んでいません。防寒対策もありません。
　戦闘用大鎌はスタミナ消費が激しくスタックしやすいためスキルレベルが上がるまで使わないほうがいいかもしれません…

■追加本
・本(武術/死神の練習曲)
　グリムリーパー修得用の武術本です。
　民家や図書館にある小説棚に低確率で入っています。
・本(学習/金と紫の大鎌)
　アーティファクト効果を持つ鎌のレシピが2つ掲載された製作6→7のスキル本です。
　図書館のスキル本棚の他や病院のベッドにごく低確率で入っています。

■追加武器
　大鎌共通の特徴として容積や重量があり、性能に比べて攻撃コストが重めです。スタミナ消費も大きいです。
　しかし追加武器各種は受け流しを持つため、武術の受動バフと重ねて防御的な動きが可能です。
　詳しい性能はtools.jsonを、レシピや詳しいレシピ習得法はrecipe.jsonを参照のこと。
・戦闘用大鎌・改
　戦闘用大鎌の容積と重量を削減、攻撃コストを軽減したものです。
　レシピは製作4近接戦闘3で習得。
・戦闘用大鎌・真
　改を全体的に強化したものです。上位4種への基点になります。性能は刀と野太刀の中間くらい？
　レシピは製作6近接戦闘5斬撃武器3で習得。
・メメント・モリ
　いわゆるダイヤモンド武器の鎌バージョンです。
　レシピは本(学習/研究日誌(グスタフ))に。
　本体のダイヤモンド武器は仕様変更により削除されましたがせっかく名前を揃えたのでそのままにしておきます。
・カルペ・ディエム(オフ/オン)
　いわゆる発火武器の鎌バージョンです。
　レシピは本(学習/溶接と製錬)と本(学習/内燃機関の基礎)に。
・ヴァニタス・ヴァニタートゥム
　アーティファクト武器その1です。非ゾンビを攻撃した時に体力を吸収できます。
　レシピは本(学習/金と紫の大鎌)に。
・栄枯盛衰
　アーティファクト武器その2です。性能は微妙ですが手にしている間ステータスと速度が上昇し精神攻撃耐性を得ます。
　レシピは本(学習/金と紫の大鎌)に。

大鎌━━戦闘用大鎌━━戦闘用大鎌・改━━戦闘用大鎌・真┓
┏━━━━━━━━━━━━━━━━━━━━━━━━━━┛
┣━メメント・モリ
┣━カルペ・ディエム
┣━ヴァニタス・ヴァニタートゥム
┗━栄枯盛衰

◆CDDAJP_Discode_TEAMからの追記
=======================
2022/12/05
0.G安定板への対応をしました
2020/09/06
0.E開発版#10980への対応をしました
2020/08/12
0.E安定版対応をさせて頂きました
また、modinfoのメンテナーを追加しました
2023/03/16
0.G安定版対応をさせて頂きました
また、looks_likeで各種鎌にタイルを設定し、
体裁も一部整えました

=======================

17/3/02
本体から削除されたアイテムを含むレシピを変更 武術本出現率を増加 その他調整
16/7/08
martial_arts_manuals.jsonの記述を0.C-5217を参考に変更("use_action": "MA_MANUAL"の位置)
16/6/17
#5046の変更点Item quality CUT implies knife actionsに則って修正