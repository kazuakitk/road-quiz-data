# 帰属表示

このデータセットを利用するソフトウェアは、以下の表示を行ってください。

## 必須

```
© OpenStreetMap contributors
```

道路の線形・通り名・路線番号は OpenStreetMap に由来します。
OpenStreetMap のデータは [ODbL 1.0](https://opendatacommons.org/licenses/odbl/1-0/) で提供されており、
本データセットもその派生データベースとして同じ ODbL 1.0 で提供されます。

地図として描画したもの（画面・画像・印刷物）は ODbL でいう Produced Work にあたり、
上記の帰属表示を行えば任意のライセンスで配布できます。

## 街道データについて（`kaido.json`）

```
『江戸主要街道データセット』（ROIS-DS人文学オープンデータ共同利用センター作成）
doi:10.20676/00000452
```

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja) で提供されています。
**OpenStreetMap 由来ではない**ため ODbL の対象外で、上記の表示が必須です。
出典: https://codh.rois.ac.jp/historical-gis/edo-road/

## 宿場データについて（`shukuba.json`）

```
『江戸宿場データセット』（ROIS-DS人文学オープンデータ共同利用センター作成）
doi:10.20676/00000477
```

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.ja) で提供されています。

## 高速道路の路線一覧・路線番号について

```
ウィキペディア「日本の高速道路一覧」「高速道路ナンバリング」
```

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.ja)。
`expressways.json` / `tollroads.json` の `official`（正式な路線名）と
`number`（路線番号）がこれに当たります。ジオメトリは OpenStreetMap（ODbL）です。

## 起点・終点データについて

```
出典: e-Gov法令検索「一般国道の路線を指定する政令」（昭和四十年政令第五十八号）
```

法令であり著作権の対象外です（著作権法第13条）。表示は任意ですが、出典として明記することを推奨します。

## 他社地図の上に重ねて表示する場合

本データを Google マップなど他社の地図基図に重ねて表示する場合、
その地図提供者が要求する帰属表示（ロゴ・著作権表示）と、
上記の `© OpenStreetMap contributors` の**両方**を表示してください。
街道データを表示する場合は『江戸主要街道データセット』の表示も加えてください。
