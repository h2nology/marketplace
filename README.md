# h2nology Claude Code Marketplace

h2nology が管理する Claude Code プラグインのマーケットプレイスです。

## 使い方

```text
/plugin marketplace add h2nology/marketplace
/plugin install quiesco@h2nology
```

更新を取り込むには:

```text
/plugin marketplace update h2nology
```

## プラグイン一覧

| 名前 | 説明 | リポジトリ |
| --- | --- | --- |
| `quiesco` | Expo アプリ向け Quiesco の e2e テストの導入（`/quiesco:setup`）、テスト作成、失敗の調査（`/quiesco:debug`） | [h2nology/quiesco](https://github.com/h2nology/quiesco) |

## プラグインの追加

`.claude-plugin/marketplace.json` の `plugins` にエントリを追加し、次で検証してください。

```bash
claude plugin validate .
```
