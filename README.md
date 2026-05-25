# ☂️ 傘いる？チェッカー

今週の出勤スケジュールを登録して、傘が必要かどうかをまとめて確認できるWebアプリです。

## 特徴

- **APIキー不要** — [Open-Meteo](https://open-meteo.com) の無料天気データを使用
- **7日先まで対応** — 週間予報をカバー
- **スケジュール保存** — 曜日・出発/帰宅時刻をブラウザに記憶
- **傘判定3段階** — 「傘が必要」「念のため持参」「傘は不要」

## 使い方

1. 都市名を入力して場所を設定（または現在地ボタン）
2. 各曜日の出勤ON/OFFと出発・帰宅時刻を設定
3. 「天気予報をチェック」ボタンを押す

## 技術

- 純粋なHTML/CSS/JavaScript（フレームワーク不要）
- [Open-Meteo Forecast API](https://open-meteo.com/en/docs)
- [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api)
- [BigDataCloud Reverse Geocoding API](https://www.bigdatacloud.com/geocoding-api)
