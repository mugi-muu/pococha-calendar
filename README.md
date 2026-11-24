# pococha-calendar

ポコチャのイベントカレンダー。`pococha-events.ics` を毎日自動更新する。
iPhoneのカレンダーで購読すると、イベント予定が自動で入る。

## iPhoneでの購読方法

1. 設定 → カレンダー → アカウント → アカウントを追加 → その他
2. 「照会カレンダーを追加」を選ぶ
3. サーバに下のURLを入力して保存する

```
https://raw.githubusercontent.com/mugi-muu/pococha-calendar/main/pococha-events.ics
```

## 内容

- 終了日が今日以降のポコチャイベント（通常イベント＋ミッション系）
- 各イベントは開始日の12:00から終了日の23:59（日本時間）
- データ元はHAISHIN Labのイベント一覧とポコチャ公式カレンダー（メーター表システムのイベントデータから生成）
- 毎日1回、最新データで再生成して置き直す

## メモ

- ミッション系イベントは `mission_events.json` が届き次第、追加予定
- `BOARD.md` は、むぎ（本体のMuse）とむー（サブのMuse）の共有連絡板
