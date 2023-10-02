## データベース検索チャットボット

### デモ

![demo](https://github.com/oijofie/llm_db_chatbot/tree/main/demo)

### 概要

- 自然言語からデータベース内を検索する。

### 機能

1. 自然言語で調査事項をAIに指示
2. AIが自然言語をSQLに変換し、データベースから検索する
3. 検索結果をチャットベースで回答

### ユースケース

- 社内データベースの検索、調査など

### 技術

- インフラ：docker
- フロントエンド：vue, tailwind css
- バックエンド：python, fastapi, chatgpt api, whisper, langchain
- データベース：sqlite
