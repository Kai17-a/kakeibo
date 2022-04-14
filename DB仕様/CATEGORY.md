# 自作家計簿アプリ

## DB詳細

## １．概要
ユーザーが登録した摘要を保持するテーブル

## ２．テーブル項目

| field | PK | unique | isNULL | type | description |
| :-- | :-: | :-: | :-: | :-: | :-- |
| category_code | - | - | - | char(2) | 摘要 |
| category_name | - | - | - | varchar | 内容名称 |
| user_id | ○ | - | - | int | ユーザー紐づけの番号 |
| desctiption | - | - | ○ | varchar | 明細の説明 |
