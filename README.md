# Claude Code ワークスペース

このディレクトリで Claude Code CLI を使うためのワークスペースです。

## 使い方

### 1. 初回ログイン（1回だけ）

PowerShell でこのフォルダを開き、以下を実行してください。

```powershell
cd "C:\claude_neko"
claude
```

初回起動時にブラウザが開き、Anthropic アカウントでのログインを求められます。
（Claude Pro / Max / Team / Enterprise または Console アカウントが必要です）

### 2. 2回目以降

`start-claude.bat` をダブルクリックするか、PowerShell で以下を実行します。

```powershell
cd "C:\claude_neko"
claude
```

## 便利なコマンド

| コマンド | 説明 |
|---------|------|
| `claude` | 対話モードを開始 |
| `claude "タスク内容"` | 1回だけタスクを実行 |
| `claude -c` | 直前の会話を続ける |
| `/login` | 再ログイン |
| `/help` | ヘルプ表示 |

## インストール情報

- Claude Code: winget (`Anthropic.ClaudeCode`)
- Git: winget (`Git.Git`)
