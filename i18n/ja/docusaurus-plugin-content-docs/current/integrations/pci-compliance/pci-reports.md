---
id: pci-reports
---

# PCI レポート

ダッシュボードや Scheduled Search
とは異なり、レポートは変更できるため、次のことを柔軟に行うことができます。

* **長期的な傾向を確認する。**レポートの時間範囲を変更して、ダッシュボードの表示範囲を超える追加の情報を取得できます。
* **変更してより詳細な情報を取得する。**単一ホスト上のイベントに関する追加の情報が必要な場合や、ユーザ
    アクティビティの詳細を確認しようとする場合、クエリを少しだけ編集すれば、レポートで非常にきめ細かな情報を得ることができます。編集したレポートは、そのまま保存済み検索として保存することを選択できます。
* **作業の集中。**デプロイ内のあるエリアのコンプライアンスを維持することが難しい場合は、的を絞ったレポートをより高い頻度で実行します。

## レポートがダッシュボードに含まれない理由

レポートは、非常に特定的できめ細かな情報を提供するように設計されています。また、検索結果に個々のログ
メッセージを返すため、これらの情報は必ずしも集計されているとは限りません。

レポートは、ダッシュボードでの一定の検索結果で明らかになった情報を強化するツールと考えてください。

## 含まれている PCI レポート

PCI コンプライアンス用 Sumo Logic
アプリケーションには、次のレポートが含まれています。

* Account Access Activity (アカウント アクセス アクティビティ)。
* Account Management Activity (アカウント管理アクティビティ)。
* Actions by Privileged Accounts (特権アカウント別のアクション)。
* Audit Log Cleared (クリアされた監査ログ)。
* AV Failed Updates (失敗したアンチウイルスの更新)。
* AV Malware Activity (アンチウイルス マルウェア アクティビティ)。
* Network Device Configuration Changes (ネットワーク
    デバイスの設定変更)。
* Network Incident Report (ネットワーク インシデント レポート)。
* Potential Credit Card Data Found
    (クレジットカードの可能性がある検出データ)。
* Prohibited Service Activity (禁止されているサービス
    アクティビティ)。
* Software Updates (ソフトウェアの更新)。
* System Time Change (システム時間の変更)。

これらのすべてのレポートは、アドホックで実行することも、Scheduled Search
として保存することもできます。
