﻿eraTW4.780用 デイリーイベント最大数指定法変更パッチ

デイリーイベントの最大定義数の指定法をDEFINEマクロに置き換え、
デイリー発生判定のシャッフル配列サイズおよびFORループ数との齟齬を無くしました。
これによりデイリーイベントの発生率がいくらか上昇します。
（各デイリーの発生判定が確実に実行されるため、何も発生しない率が下がるはず）

最大数の値については、更新履歴見ると「40に水増し」となっていたので40としておきました
