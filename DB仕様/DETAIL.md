# 自作家計簿アプリ

## DB詳細

## １．概要
ユーザーが登録した明細を保持するテーブル。

## ２．テーブル項目

| field | PK | unique | isNULL | type | description |
| :-- | :-: | :-: | :-: | :-: | :-- |
| detail_id | ○ | ○ | - | int | 明細番号 |
| category_id | - | - | - | int | 摘要 |
| payment_id | - | - | - | - | 支払い方法 |
| user_id | ○ | - | - | int | ユーザー紐づけの番号 |
| money | - | - | - | int | 金額 |
| date | - | - | - | varchar | 保存した年月日（YYYY/MM/DD） |
| desctiption | - | - | ○ | varchar | 明細の説明 |

