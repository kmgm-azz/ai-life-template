# AI Life Template

やりたいことやメモをGitHub Issuesへ集め、AIとの会話で整理・更新するための個人用テンプレートです。

- 「あとでやりたい」→ Issueにする
- 「今から何をすればいい？」→ 未完了Issueから提案する
- 「始めた／終わった」→ 進捗を更新する

## 始め方

1. このページの **Use this template** → **Create a new repository** から、自分用のリポジトリを作ります。生活の予定や個人的なメモを入れる場合は **Private** を推奨します。
2. [Projectsの雛形](https://github.com/users/kmgm-azz/projects/2)を **Make a copy** でコピーし、Project名を `life` にします。
3. 作成したリポジトリを読み書きできるAIへ、次のように頼みます。

> このリポジトリのAGENTS.mdを読んで、必要なラベルを確認・作成し、Project「life」と連携してください。

GitHubアカウントと、GitHub連携またはローカルGitを操作できるAI環境が必要です。通常のAIチャットだけではGitHubを更新できません。

## 普段の使い方

特別な書式は必要ありません。AIへ普通に話しかけます。

```text
富士山に登りたい。準備をあとで整理したい。
ブログの構想をIssueにして。
今から何をすればいい？
競技プログラミングの教材を始めた。進捗を反映して。
```

詳しい会話例は[examples/conversations.md](examples/conversations.md)にあります。

## 仕組み

- `AGENTS.md`: AIへの運用ルール
- GitHub Issues: タスクやアイデア
- GitHub Projects: 一覧と進捗
- `daily/`・`ideas/`・`references/`: Markdownで残す記録

使い方を変えたいときは、AIへ相談しながら`AGENTS.md`を更新してください。

## 注意

- APIキー、トークン、パスワード、個人情報を書かない
- 公開リポジトリで生活予定や私的なIssueを扱わない
- AIが作成・更新した内容は、外部公開前に確認する

## ライセンス

[MIT License](LICENSE)
