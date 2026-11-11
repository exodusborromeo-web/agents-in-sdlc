---
title: "GitHub Copilot クラウド エージェント"
slug: ja-jp/real-world-development/cloud
authors:
  - geektrainer
lastUpdated: 2026-06-30
---

[GitHub Copilot クラウド エージェント](https://docs.github.com/copilot/concepts/agents/cloud-agent/about-cloud-agent)を使うと、GitHub Copilot がクラウドで非同期に作業できます。GitHub で作業を割り当てると、クラウド エージェントはバックグラウンドでリポジトリを調べ、変更を行い、pull request を作成します。その間、別の作業を続けられます。

各演習では、まずクラウド エージェントが従うカスタム指示を追加し、その後 GitHub issue を割り当てて実装を依頼します。カスタム エージェントをレビューして作業の進め方を調整し、エージェント ダッシュボードからセッションを監視、誘導した後、pull request をレビューして結果を反復的に改善します。

## 演習

| 演習 | トピック | 説明 |
|----------|-------|-------------|
| [0. 前提条件][ex0] | セットアップ | リポジトリと codespace を作成します |
| [1. カスタム指示][ex1] | コンテキスト | クラウド エージェントが従うカスタム指示を追加します |
| [2. クラウド エージェント][ex2] | 非同期エージェント | GitHub Copilot クラウド エージェントに issue を割り当てます |
| [3. カスタム エージェント][ex3] | 特化型エージェント | カスタム エージェントをレビューして使用します |
| [4. エージェントの管理][ex4] | 監視 | エージェント セッションを監視して誘導します |
| [5. 反復][ex5] | レビュー | pull request をレビューし、Copilot の作業を反復して改善し、次の手順を選択します |

## 前提条件

このワークショップに参加する前に、次のものを用意してください。

- [ ] **Copilot Student、Pro、Pro+、Business、Enterprise** のいずれかの有効なプランがある GitHub アカウント
- [ ] アカウントまたは組織で有効になっている GitHub Copilot クラウド エージェント

> [!TIP]
> 有料プランをお持ちでない場合、認証済みの学生は[GitHub Education][callout-student-plan-education]を通じて GitHub Copilot を無料で利用できます。**Copilot Student** プランには、このワークショップで使用するエージェント、MCP、コード レビュー、Copilot CLI の機能が含まれているため、すべてのハーネスを完了できます。

[callout-student-plan-education]: https://github.com/education/students

> [!NOTE]
> クラウド エージェントは **Copilot Student、Pro、Pro+、Business、Enterprise** で利用できます。Copilot Free では利用できません。Copilot Business または Enterprise では、管理者が組織で有効にする必要があります。

> [!NOTE]
> このハーネスでは MCP を扱いません。Copilot で MCP サーバーを使う方法については、[CLI ハーネス](../cli/)または [VS Code ハーネス](../vscode/)を参照してください。

## 開始する

**[演習 0: 前提条件から開始 →][ex0]**

[ex0]: 0-prerequisites/
[ex1]: 1-custom-instructions/
[ex2]: 2-cloud-agent/
[ex3]: 3-custom-agents/
[ex4]: 4-managing-agents/
[ex5]: 5-iterating/
