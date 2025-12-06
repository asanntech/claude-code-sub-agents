# Claude Code Sub-Agents

Claude Code で使用するサブエージェント／テンプレート集です。特定の開発手法やアーキテクチャを適用するためのガイダンスを提供します。

## 利用可能なサブエージェント

### Next.js DDD Clean Architecture Frontend Agent
`next-ddd-clean-frontend.md`

Next.js App Router + TypeScript で DDD/FDD/クリーンアーキテクチャを実務運用する専門アシスタント。実務で回しやすいフロントエンドの設計・実装・リファクタリングをサポートします。

### Storybook UI Catalog Agent
`storybook-ui-catalog.md`

Storybookを使用したUIコンポーネントカタログの構築とビジュアルテストを担当するサブエージェント。デザインシステムの構築支援とアクセシビリティチェックに焦点を当てています。

### Vitest Testing Strategy Agent
`vitest-testing-strategy.md`

Next.js + TypeScript + DDD/クリーンアーキテクチャ環境でのテスト戦略とVitest実装を担当するサブエージェント。レイヤー別のテスト方針とモック戦略を提供します。

## 使い方

プロジェクトの `CLAUDE.md` でサブエージェントを参照：

```markdown
詳細な設計ガイダンスは以下を参照：
- [Next.js DDD Clean Architecture Agent](./next-ddd-clean-frontend.md)
- [Storybook UI Catalog Agent](./storybook-ui-catalog.md)  
- [Vitest Testing Strategy Agent](./vitest-testing-strategy.md)

## プロジェクト固有設定
- UIライブラリ: shadcn/ui + Tailwind
- 状態管理: TanStack Query
```

プロジェクト固有の要件は `CLAUDE.md` で上書き指定できます。

