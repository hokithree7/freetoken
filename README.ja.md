# FreeToken.link — 無料枠のあるLLM APIルートを探して検証する

[English](README.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [한국어](README.ko.md)

[![FreeToken.link overview](assets/freetoken-overview.png)](https://freetoken.link/ja)

**FreeToken.link は、日付付きの無料利用条件を比較し、公式のAPIキー取得手順を確認し、対応ルートをブラウザから直接テストし、実際のキーを含まない設定テンプレートを作成できる開発者向けツールです。重要な変更を追跡する Watchlist も構築できます。**

日本語版: **[freetoken.link/ja](https://freetoken.link/ja)**

> この公開リポジトリは、製品説明・公開資料・フィードバック用です。本番ソースコード、プロバイダー認証情報、共有APIキー、ユーザーのVaultデータ、運用シークレットは公開しません。

## AIアシスタントから使う

読み取り専用の **FreeToken MCP Server** を公開しました。公式 MCP Registry に [`link.freetoken/catalog`](https://registry.modelcontextprotocol.io/v0.1/servers/link.freetoken%2Fcatalog/versions/1.0.0) **v1.0.0** として登録されています。

Streamable HTTP 対応クライアントに **`https://freetoken.link/mcp`** を追加します。FreeToken のアカウントやAPIキーは不要です。公開モデルの検索、公式の申請手順、日付付き価格情報、費用の概算、既存のチェック結果、キーを含まない設定の取得に対応します。推論、キーのテスト、リアルタイムの稼働確認、非公開Vaultへのアクセスは行いません。ツールの説明文は現在英語で、locale はサイト内リンクの言語を指定します。

[日本語の接続ガイド](https://freetoken.link/ja/mcp-guide) · [ツールと制限事項（英語）](docs/MCP.md)

## 特徴

- [要件からAPIを探す（英語）](https://freetoken.link/find)
- [モデルとプロバイダーを絞り込む](https://freetoken.link/ja/models)
- [公式のAPIキー取得手順を確認する](https://freetoken.link/ja/get-key)
- [既存キーをブラウザから直接診断する](https://freetoken.link/ja/doctor)
- [ブラウザから直接プロンプトを試す](https://freetoken.link/ja/playground)
- [実際のキーを含まない設定を作成する](https://freetoken.link/ja/playground#tool-config)
- [価格情報を比較する](https://freetoken.link/ja/pricing)
- [既存の稼働チェック結果を確認する](https://freetoken.link/ja/status)
- [可用性と無料条件の変更を監視する](https://freetoken.link/ja/watchlist)
- [情報源と検証方法を確認する](https://freetoken.link/ja/sources)

## 信頼とプライバシー

FreeToken は、公式ドキュメントの主張と FreeToken が運用する Canary の観測結果を分けて表示します。対応するブラウザ直接テストでは、APIキーとプロンプトはブラウザから選択したプロバイダーへ送信され、共有URLにはキーを含めません。スクレイピング、転売、共同利用されたAPIキーは提供しません。

誤ったモデルID、古い利用条件、壊れた公式リンクを見つけた場合は、公式情報源と確認日を添えて Source correction Issue を作成してください。APIキーや個人情報は投稿しないでください。

製品とSEOの canonical は常に `https://freetoken.link/` です。このリポジトリは透明な説明、引用、開発者からのフィードバックのために使用します。
