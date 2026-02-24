# 【目次】
1. [最終更新](https://github.com/Ukun115/StudentProductions?tab=readme-ov-file#%E6%9C%80%E7%B5%82%E6%9B%B4%E6%96%B0)
2. [開発者情報](https://github.com/Ukun115/StudentProductions?tab=readme-ov-file#%E9%96%8B%E7%99%BA%E8%80%85%E6%83%85%E5%A0%B1)
3. [ゲームランチャーDLから起動まで](https://github.com/Ukun115/StudentProductions?tab=readme-ov-file#%E3%82%B2%E3%83%BC%E3%83%A0%E3%83%A9%E3%83%B3%E3%83%81%E3%83%A3%E3%83%BCdl%E3%81%8B%E3%82%89%E8%B5%B7%E5%8B%95%E3%81%BE%E3%81%A7)
4. [ゲームランチャー起動からゲーム起動まで](https://github.com/Ukun115/StudentProductions?tab=readme-ov-file#%E3%82%B2%E3%83%BC%E3%83%A0%E3%83%A9%E3%83%B3%E3%83%81%E3%83%A3%E3%83%BC%E8%B5%B7%E5%8B%95%E3%81%8B%E3%82%89%E3%82%B2%E3%83%BC%E3%83%A0%E8%B5%B7%E5%8B%95%E3%81%BE%E3%81%A7)
5. [DLしたゲームは何処へ](https://github.com/Ukun115/StudentProductions?tab=readme-ov-file#dl%E3%81%97%E3%81%9F%E3%82%B2%E3%83%BC%E3%83%A0%E3%81%AF%E4%BD%95%E5%87%A6%E3%81%B8)
6. [ゲームランチャー詳細](https://github.com/Ukun115/StudentProductions?tab=readme-ov-file#%E3%82%B2%E3%83%BC%E3%83%A0%E3%83%A9%E3%83%B3%E3%83%81%E3%83%A3%E3%83%BC%E8%A9%B3%E7%B4%B0)
7. [ゲームランチャーバージョン表記規則](https://github.com/Ukun115/StudentProductions?tab=readme-ov-file#%E3%82%B2%E3%83%BC%E3%83%A0%E3%83%A9%E3%83%B3%E3%83%81%E3%83%A3%E3%83%BC%E3%83%90%E3%83%BC%E3%82%B8%E3%83%A7%E3%83%B3%E8%A1%A8%E8%A8%98%E8%A6%8F%E5%89%87)
8. [Releases構成](https://github.com/Ukun115/StudentProductions?tab=readme-ov-file#releases%E6%A7%8B%E6%88%90)

---

# 【最終更新】
## 2025/12/09(火)
【v1.0.0】ゲームランチャー試作品完成

【v1.1.0】002ゲーム追加

## 2025/12/13(土)
【v1.2.0】003ゲーム追加

## 2026/01/15(木)
【v1.3.0】004～012ゲーム追加

## 2026/01/19(月)
【v1.3.1】作品名/開発者名のテキストスクロールやパッケージ追加など

【v1.4.0】013ゲーム追加

## 2026/01/20(火)
【v1.5.0】014ゲーム追加

【v1.6.0】ローディングUI追加。ゲームをDL中、進捗状況がプログレスバーで可視化された。

## 2026/02/23(月)
【v1.6.1】ローディングの進捗度合いを%表示 / 学生作品マスターデータの項目追加 / 実行ファイルのアイコンを河原アイコンへ変更 / 学生作品の追加方法を簡略化 / 6000.0.58f2→6000.3.9f1バージョンアップ / Readme更新 / リファクタ

## 2026/02/24(火)
【v1.6.2】ビルド&Zip作成までをエディタ拡張で自動化

---

# 【開発者情報】
- 伊関 拓夢(いせき たくむ)
- GC教員
- 要望、不具合バグ報告、ゲーム追加依頼等ありましたらTeamsDMや[Issues](https://github.com/Ukun115/StudentProductions/issues)、[自由チャット](https://github.com/Ukun115/StudentProductions/discussions/1)からご連絡お願いいたします。

---

# 【ゲームランチャーDLから起動まで】
1. Releases/GameLauncher/GameLauncher_vX.X.X.zipをDL

　　※最新バージョン推奨

2. DLしたzipファイルを展開
3. GameLauncher.exeからランチャー起動

---

# 【ゲームランチャー起動からゲーム起動まで】
1. 学生作品ボタン押す
2. スクロールビュー内の学生作品をクリック
3. zipの自動DLが始まります。
4. zipのDL完了→自動展開→ゲームが起動します。

※DLしたzipは不要なため自動削除しています。

※GitHub/ReleasesにアクセスしDLしてくるため、Wi-Fi環境必須です。

---

# 【DLしたゲームは何処へ】
C:\Users\ユーザー名\AppData\LocalLow\KBC_GC_Launcher\Gamesに格納。

容量の都合でゲームを削除したい場合はこのパスからゲームを削除しに行ってください。

※「AppData」は隠しファイルです。見当たらない場合は表示してください。

---

# 【ゲームランチャー詳細】
サイズ：187MB

ゲームランチャープロジェクト：https://github.com/Ukun115/GameLauncher

---

# 【ゲームランチャーバージョン表記規則】
## Base：vX.Y.Z(セマンティックバージョニング)

### X(メジャーバージョン)　→　互換性を壊すような大規模な変更など

ex. 開発者上項目の追加、学生作品フィルタリング機能追加

### Y(マイナーバージョン)　→　既存の互換性を壊さず新要素を追加したときなど

ex. 学生作品追加、マスターデータの属性追加

### Z(パッチバージョン)　　→　バグ修正や微調整、ゲームランチャーの性能事態に影響の少ない変更など

ex. レイアウトの調整、ボタン連打対策

## その他注意
- 例えばv2.5.0の場合、「v2.5」のように0を省略しないでください。正 ) v2.5.0

---

# 【Releases構成】
## GameLauncher
- ゲームランチャー本体
- 使用方法は同Readmeに記述

## 001～
- 各学生のゲームexe
