---
title: "実践的な開発"
slug: ja-jp/real-world-development
authors:
  - geektrainer
lastUpdated: 2026-09-16
---

現実的なシナリオ、完成したアプリケーション、共有バックログを使って、ソフトウェア開発ライフサイクル全体で GitHub Copilot を体験します。変更を計画し、コードを作成し、動作をテストし、プルリクエストをレビューし、エージェントで作業を管理する反復型の開発を行います。

## シナリオ

開発者をテーマにしたボードゲームのクラウドファンディングを提供する架空の会社、Tailspin Toys の新しい開発者として作業します。チームのバックログは GitHub Issue として登録済みで、すぐに取り組めます。フィルタリングやページネーションなどの機能に加え、アクセシビリティやコーディング標準などの品質改善も含まれています。

## 作業環境を選ぶ

GitHub Copilot はさまざまな作業環境で使えます。開発方法に合った環境を選択してください。各ワークショップはそれぞれのセットアップから始まり、共通の Tailspin Toys シナリオを使用します。

### [GitHub Copilot CLI][cli]

ターミナルでエージェント型アシスタントを使います。Plan モードと Autopilot モード、指示、スキル、カスタム エージェント、Playwright MCP、Agent Merge、実用的なスラッシュ コマンドを扱います。

### [GitHub Copilot app][app]

エージェント セッションを並行して実行し、セッション モードを切り替え、キャンバスで共同作業し、デスクトップ アプリで GitHub Issue とプルリクエストを管理します。

### [GitHub Copilot cloud agent][cloud]

GitHub Issue を非同期エージェントに割り当て、作業をガイドし、進行状況を監視し、エージェントが作成したプルリクエストをレビューします。

### [Visual Studio Code][vscode]

Visual Studio Code と GitHub Codespaces で GitHub Copilot を使います。エディターを離れずに Copilot Chat のエージェント モード、MCP サーバー、カスタム エージェントを扱います。

[cli]: cli/
[app]: app/
[cloud]: ../../real-world-development/cloud/
[vscode]: vscode/
