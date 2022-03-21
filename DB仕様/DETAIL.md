# 自作家計簿アプリ

## DB詳細

## １．概要
ユーザーが登録した明細を保持するテーブル。

## ２．テーブル項目

| field | PK | unique | isNULL | type | description |
| :-- | :-: | :-: | :-: | :-: | :-- |
| user_id | ○ | - | - | int | ユーザー紐づけの番号 |
| payment_code | - | - | - | char(2) | 支払い方法 |
| category | - | - | - | char(2) | 摘要 |
| money | - | - | - | int | 金額 |
| desctiption | - | - | ○ | varchar | 明細の説明 |
| add_date | - | - | - | char(8) | 保存した年月日（YYYY/MM/DD） |
| version_number | - | - | - | int | 楽観排他用バージョン番号 |

