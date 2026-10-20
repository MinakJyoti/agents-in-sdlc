---
slug: ja-jp/real-world-development/cli
title: "GitHub Copilot CLI"
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

**[GitHub Copilot CLI](https://docs.github.com/copilot/concepts/agents/about-copilot-cli)** は、ターミナルで GitHub Copilot をエージェント型のコーディング アシスタントとして利用できるようにします。コードベースを探索し、コードを生成し、コマンドを実行し、外部ツールに接続できます。すべてコマンド ラインから行えるため、グラフィカル エディターに切り替えずに作業の流れを保てます。

このワークショップでは、Tailspin Toys で一連の開発作業を進めます。GitHub Codespaces でプロジェクトを準備し、星評価を追加した後、issue を起点にフィルター機能を実装します。Plan モードで方針を決め、Autopilot で実装し、Interactive でレビューします。さらに、リポジトリの指示を更新し、`quality-checks` スキルをカスタマイズし、Playwright MCP でフィルターを検証し、QA カスタム エージェントを作成して最終 PR をレビューします。ワークショップでは、星評価用とフィルターおよび品質作業用の 2 つの PR を作成します。[GitHub Copilot CLI と Foundry を使う全 3 モジュールのオプション シリーズ][foundry]では、モデルを準備し、ホスト型エージェントを構築してデプロイし、サイトに統合できます。

## 演習

| 演習 | トピック | 説明 |
|----------|-------|-------------|
| [0. 前提条件][ex0] | セットアップ | リポジトリと codespace を作成する |
| [1. Copilot CLI のインストール][ex1] | インストール | Copilot CLI をインストールして認証する |
| [2. 星評価を追加する][ex2] | 最初の変更 | 既存の評価を表示し、最初の PR をマージする |
| [3. エージェント モード: Plan と Autopilot][ex3] | エージェント モード | issue から機能を計画し、実装してレビューする |
| [4. カスタム命令で Copilot を導く][ex4] | コンテキスト | 命令を更新し、フィルター機能に適用する |
| [5. quality-checks スキルをカスタマイズして使う][ex5] | チェック | 既存のスキルをカスタマイズして実行する |
| [6. Playwright MCP で機能を検証する][ex6] | ブラウザーでの確認 | MCP を構成し、フィルターの動作を確認する |
| [7. QA エージェントを作成して使う][ex7] | 要件とカバレッジ | 要件、カバレッジ、検証の証拠を確認する |
| [8. 機能 PR を作成してマージする][ex8] | レビューとマージ | 変更全体をレビューし、Agent Merge を使う |
| [9. GitHub Copilot CLI のスラッシュ コマンド][ex9] | CLI 機能 | コンテキスト、モデル、共有を確認する |
| [10. 振り返りと次のステップ][ex10] | まとめ | 作業の流れと追加リソースを確認する |
| [オプション: Foundry を組み込む][foundry] | ホスト型エージェント | モデルを準備し、カタログに基づくエージェントをデプロイして Web サイトに接続する |

## 前提条件

このワークショップに参加する前に、次を準備してください。

- [ ] **Copilot Student、Pro、Pro+、Business、Enterprise** のいずれかの有効なプランがある GitHub アカウント
- [ ] ターミナル / コマンド ライン操作の基本的な知識
- [ ] インストール済みで設定済みの Git

> [!TIP]
> 有料プランがありませんか。認証済みの学生は [GitHub Education][callout-student-plan-education] を通じて GitHub Copilot を無料で利用できます。**Copilot Student** プランには、このワークショップで使用する agent、MCP、code review、Copilot CLI の機能が含まれているため、すべての harness を完了できます。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> Copilot Business または Copilot Enterprise を使用している場合は、管理者が Copilot CLI を有効にしていることを確認してください。

## はじめる

**[演習 0: 前提条件から始める →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-install-copilot-cli/
[ex2]: 2-add-star-rating/
[ex3]: 3-agent-modes/
[ex4]: 4-custom-instructions/
[ex5]: 5-agent-skills/
[ex6]: 6-mcp-playwright/
[ex7]: 7-qa-agent/
[ex8]: 8-create-pull-request/
[ex9]: 9-cli-power-tools/
[ex10]: 10-review/
[foundry]: 8-foundry-agent/
