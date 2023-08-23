# snsdeck

ElectronによるTweetDeckのようなSNS Viewer

![image](https://github.com/meganii/snsdeck/assets/329554/ba5742f1-d6fa-4634-8137-17b6967b4d69)


## 使い方

```
npm install
npm start
```

- 「Add Column」ボタンから開く小画面でURLとUserCSS（任意）を入力して、「Add Column」を押すとカラム追加
  - 追加したカラム情報は、`electron-store`のデフォルトパスに保存


## 変更点(by SennoMotokazu)
現状では設定化していないので下記の挙動で固定です
- Twitterのホームタイムラインのスクロールが一番上の時、自動更新するよう変更
- リンクをOSのデフォルトブラウザで開くよう変更

