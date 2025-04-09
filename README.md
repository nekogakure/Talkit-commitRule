# Talkit-commitRule

## フォーマット

```
[カテゴリ] [内容（簡潔に）]
```

### 例

- `FEAT 投稿機能に動画添付を追加`
- `FIX ログイン後に404が出る不具合修正`
- `REFACTOR API呼び出し部分を共通化`
- `DOCS READMEに環境構築手順を追加`
- `STYLE インデントとコメント整形`
- `TEST 投稿のバリデーションテスト追加`

---

## カテゴリ一覧

| タグ        | 説明                                       |
|-------------|--------------------------------------------|
| FEAT        | 新機能追加                                 |
| FIX / BUGFIX| バグ修正                                   |
| REFACTOR    | リファクタリング（挙動は変えずコード整理）|
| DOCS        | ドキュメント・READMEなどの変更             |
| STYLE       | フォーマット修正（インデントや改行など）   |
| TEST        | テストの追加・修正                         |
| CHORE       | 雑務（CI設定、依存追加など）               |
| REMOVE      | 不要コード・機能の削除                     |

---

## WIP（作業途中コミット）

作業中の一時コミットには `WIP:` を先頭につけてください。

- `WIP: FEAT コメント機能追加中（未完成）`

---

## NG例（避けてください）

以下のような意味のないコミットメッセージは避けてください：

- `コミットしておきます〜`
- `デバッグのやつ`
- `修正修正修正修正`
- `疲れたからここまで`
- `aaa`

