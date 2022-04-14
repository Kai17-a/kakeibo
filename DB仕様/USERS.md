# 自作家計簿アプリ

## DB詳細

## １．概要
家計簿アプリにおける、ユーザー情報を保持するテーブル。

## ２．テーブル項目

| field | PK | unique | isNULL | type | description |
| :-- | :-: | :-: | :-: | - | :-- |
| user_id | ○ | ○ | - | int | ユーザー紐づけの番号 |
| user_name | - | ○ | - | varchar |ユーザー名 |
| user_password | - | - | - | varchar | ユーザーパスワード |
| login_date | - | - | - | date | 2重ログイン防止用カラム |
