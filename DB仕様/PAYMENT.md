# 自作家計簿アプリ

## DB詳細

## １．概要
ユーザーが登録した支払い方法を保持するテーブル。
各ユーザーが登録した支払方法が登録されるため、紐づけするユーザーIDを持つ。

## ２．テーブル項目

| field | PK | unique | isNULL | type | description |
| :-- | :-: | :-: | :-: | :-: | :-- |
| payment_id | ○ | - | - | char(2) | 支払い番号 |
| payment_code | ○ | - | - | char(2) | 支払い方法 |
| payment_name | - | - | - | varchar | 支払い方法名称 |
| user_id | ○ | - | - | int | ユーザー紐づけの番号 |
| desctiption | - | - | ○ | varchar | 支払方法の説明 |