# Claude Code Sub-Agents

Claude Code で使用するサブエージェント／テンプレート集です。特定の開発手法やアーキテクチャを適用するためのガイダンスを提供します。

## 利用可能なサブエージェント

### Next.js DDD Clean Architecture Frontend Agent
`next_ddd_clean_frontend.md`

Next.js App Router + TypeScript で DDD/FDD/クリーンアーキテクチャを実務運用する専門アシスタント。

## 使い方

プロジェクトの `CLAUDE.md` でサブエージェントを参照：

```markdown
詳細な設計ガイダンスは以下を参照：
- [Next.js DDD Clean Architecture Agent](./path/to/next_ddd_clean_frontend.md)

## プロジェクト固有設定
- UIライブラリ: shadcn/ui + Tailwind
- 状態管理: TanStack Query
```

プロジェクト固有の要件は `CLAUDE.md` で上書き指定できます。

