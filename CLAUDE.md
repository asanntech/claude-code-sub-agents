# CLAUDE.md

このファイルは、このリポジトリでコードを操作する際のClaude Code (claude.ai/code) へのガイダンスを提供します。

## 言語設定

このプロジェクトでのやり取りは日本語で行ってください。

## プロジェクト概要

これはClaude Code用のサブエージェント／テンプレート集のリポジトリです。特定の開発手法やアーキテクチャを適用するためのガイダンスを提供する専門エージェントが含まれています。

### 利用可能なサブエージェント

1. **Next.js DDD Clean Architecture Frontend Agent** (`next-ddd-clean-frontend.md`)
   - Next.js App Router + TypeScript で DDD/FDD/クリーンアーキテクチャの実装
   - 実務で回しやすいフロントエンド設計・実装・リファクタリング

2. **Storybook UI Catalog Agent** (`storybook-ui-catalog.md`)
   - Storybookを使用したUIコンポーネントカタログの構築
   - デザインシステム構築支援とアクセシビリティチェック

3. **Vitest Testing Strategy Agent** (`vitest-testing-strategy.md`)
   - Next.js + TypeScript + DDD環境でのテスト戦略
   - Vitestを使用したレイヤー別テスト方針とモック戦略

## 開発コマンド

現在、特定のビルド、テスト、またはリントコマンドは設定されていません。プロジェクト構造の発展に伴ってコマンドが追加される予定です。

## ファイル構造

```
claude-code-sub-agents/
├── README.md                      # プロジェクト概要と使用方法
├── CLAUDE.md                      # このファイル（プロジェクト指示）
├── next-ddd-clean-frontend.md     # Next.js DDD/Clean Architecture Agent
├── storybook-ui-catalog.md        # Storybook UI Catalog Agent  
└── vitest-testing-strategy.md     # Vitest Testing Strategy Agent
```

## 使用方法

プロジェクトの `CLAUDE.md` で必要なサブエージェントを参照してください：

```markdown
詳細な設計ガイダンスは以下を参照：
- [Next.js DDD Clean Architecture Agent](./next-ddd-clean-frontend.md)
- [Storybook UI Catalog Agent](./storybook-ui-catalog.md)
- [Vitest Testing Strategy Agent](./vitest-testing-strategy.md)
```

## 注意事項

- サブエージェントはプロジェクト固有の設定（UIライブラリ、状態管理等）を `CLAUDE.md` で上書き指定できます
- 複数のサブエージェントを組み合わせて使用することで、包括的な開発支援が可能です
- 各サブエージェントは相互に連携するよう設計されています（例：Next.js + Storybook + Vitest）