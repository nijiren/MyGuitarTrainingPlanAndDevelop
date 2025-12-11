# API設計

## エンドポイント一覧

### 認証エンドポイント
```
POST   /api/auth/register      - ユーザー登録
POST   /api/auth/login         - ログイン
POST   /api/auth/logout        - ログアウト
GET    /api/auth/me            - 現在のユーザー情報
PUT    /api/auth/profile       - プロフィール更新
```

### レッスンエンドポイント
```
GET    /api/lessons            - レッスン一覧
GET    /api/lessons/:id        - レッスン詳細
GET    /api/lessons/:id/progress - ユーザーの進捗取得
PUT    /api/lessons/:id/progress - 進捗更新
POST   /api/lessons/:id/complete - レッスン完了
```

### 練習ログエンドポイント
```
GET    /api/practice-logs      - ログ一覧
GET    /api/practice-logs/:id  - ログ詳細
POST   /api/practice-logs      - ログ作成
PUT    /api/practice-logs/:id  - ログ更新
DELETE /api/practice-logs/:id  - ログ削除
GET    /api/practice-logs/stats - 統計情報
```

### 音楽理論エンドポイント
```
GET    /api/scales             - スケール一覧
GET    /api/scales/:id         - スケール詳細
GET    /api/chords             - コード一覧
GET    /api/chords/:id         - コード詳細
GET    /api/chords/progression - コード進行生成
```

詳細は元の技術仕様書を参照
