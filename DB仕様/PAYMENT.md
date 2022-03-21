# 自作家計簿アプリ

## DB詳細

## １．概要
ユーザーが登録した支払い方法を保持するテーブル。
各ユーザーが登録した支払方法が登録されるため、紐づけするユーザーIDを持つ。

## ２．テーブル項目

| field | PK | unique | isNULL | type | description |
| :-- | :-: | :-: | :-: | :-: | :-- |
| payment_code | ○ | - | - | char(2) | 支払い方法 |
| payment | - | - | - | varchar | 支払い方法名称 |
| user_id | ○ | - | - | int | ユーザー紐づけの番号 |
| version_number | - | - | - | int | 楽観排他用バージョン番号 |
