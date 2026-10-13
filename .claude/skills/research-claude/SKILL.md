指定期間：2026-W

指定された期間の週次レポートを作成するため、Claude の公式の情報源を参考に、指定期間のClaudeのリリース情報をまとめてください。

その際、追加機能は省略せず全て列挙し、修正に関する項目は除外してください。

Chat GPTでこのプロンプトを受け付けた場合、回答のチャットのタイトルは「Claude yyyy-Www週次レポート」としてください。

また、回答は以下のフォーマットに従い、md形式のコードブロックで出力してください。

```
2.0.43
2025年11月17日

- カスタムエージェントに`permissionMode`フィールドを追加
- `PreToolUseHookInput`と`PostToolUseHookInput`に`tool_use_id`フィールドを追加
- Subagentが自動ロードするSkillsをfrontmatterで指定できるようになった
- `SubagentStart` Hookイベントを追加

---

2.0.45
2025年11月18日

- Microsoft Foundryに対応
- `PermissionRequest` Hookを追加
- Claude Code on the Webでバックグラウンドタスクに対応

---

2.0.49
2025年11月20日

- readline形式の`Ctrl-Y`に対応
- 使用量上限の警告メッセージを改善

---

2.0.55
2025年11月21日

- `AskUserQuestion`の動作を改善
- `@`によるファイル候補のファジー検索を改善

---

2.0.56
2025年11月22日

- ターミナルのプログレスバーを有効・無効にする設定を追加
- VS Code拡張でSecondary Sidebarに対応
- VS Code拡張でメッセージのストリーミング表示に対応

```