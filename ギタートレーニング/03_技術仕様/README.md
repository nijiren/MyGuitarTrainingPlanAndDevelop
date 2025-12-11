# 技術仕様

## ドキュメント一覧

- [システムアーキテクチャ](システムアーキテクチャ.md)
- [データベース設計](データベース設計.md)
- [API設計](API設計.md)
- [音声処理仕様](音声処理仕様.md)

## 技術スタック

### フロントエンド（Web）
- **Framework**: Next.js 14+ (App Router)
- **Language**: TypeScript 5+
- **Styling**: Tailwind CSS 3+
- **UI Components**: shadcn/ui
- **State Management**: Zustand
- **Audio Processing**: Tone.js
- **Music Notation**: VexFlow

### バックエンド
- **Runtime**: Node.js 18+
- **Framework**: Next.js API Routes
- **Database**: PostgreSQL 14+
- **ORM**: Prisma
- **Cache**: Redis 6+
- **Authentication**: NextAuth.js v5

### モバイル
- **Framework**: React Native 0.72+
- **Language**: TypeScript
- **Navigation**: React Navigation 6+
- **Audio**: react-native-sound, react-native-audio
