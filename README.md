# Project Instructions

Backlog のチケット更新（リリース申請）をトリガーに、Slack ワークフロービルダーを実行する

## アーキテクチャ（全体構成）

### API Gateway + Lambda

serverless FW を利用して API Gateway/Lambda(Node.js)を Deploy する

### Slack ワークフロービルダー

[Webhook を利用したワークフローの実行](https://slack.com/intl/ja-jp/help/articles/360041352714-Webhook-%E3%82%92%E4%BD%BF%E7%94%A8%E3%81%97%E3%81%9F%E9%AB%98%E5%BA%A6%E3%81%AA%E3%83%AF%E3%83%BC%E3%82%AF%E3%83%95%E3%83%AD%E3%83%BC%E3%82%92%E4%BD%9C%E6%88%90%E3%81%99%E3%82%8B)を利用して Web API から Slack ワークフローを実行する

#### 参考になりそうなサイト

- [Slack ワークフロービルダーの新しいトリガー（日時/Webhook）を使ってみよう！](https://qiita.com/kazushi_iizuka/items/c79cec16ded2b89a145c)
