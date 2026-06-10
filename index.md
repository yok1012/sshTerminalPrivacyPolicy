# AI Terminal プライバシーポリシー

## 事業者情報

横川貴一  
yok1012ichi@gmail.com

---

## 1. はじめに

横川貴一（以下「当社」）は、スマートフォン向けアプリケーション「AI Terminal」（以下「本アプリ」）を提供しています。本プライバシーポリシーは、本アプリにおけるユーザー情報の取得、利用、保存、管理について説明するものです。

本アプリをご利用いただくことにより、本プライバシーポリシーに同意したものとみなされます。

---

## 2. 取得する情報

本アプリは、アプリの機能提供のために以下の情報を取得または保存する場合があります。

### 2.1 SSH接続設定

- 接続名
- ホスト名またはIPアドレス
- ポート番号
- ユーザー名
- 認証方式（SSHキー、パスワード、エージェント等）
- 認証情報に関するヒントまたは参照情報
- 接続ごとの表示色
- 作成日時および更新日時

本アプリは、SSH接続を管理しやすくするためにこれらの情報を保存します。パスワードや秘密鍵などの機密情報を扱う場合は、ユーザー自身の管理責任のもとで入力してください。

### 2.2 tmux設定

- tmux自動アタッチの有効・無効
- セッション名
- ウィンドウ名
- 起動時に実行するコマンド
- デフォルトのtmuxプリセット

### 2.3 スニペット情報

- スニペットのタイトル
- コマンド本文
- カテゴリー（Claude、Git、tmux、カスタム等）
- Pro機能に関する表示情報

### 2.4 AI判断依頼・Inbox情報

- AIツールからの確認依頼内容
- 関連する接続名
- 確認依頼の詳細情報
- 作成日時
- 承認、却下、保留等のステータス

### 2.5 通知設定および通知関連情報

本アプリは、AIツールがユーザーの判断を待っている場合に通知を送信することがあります。通知機能を利用する場合、OSの通知許可状態、通知設定、および通知内容に必要な情報を利用します。

### 2.6 アプリ設定情報

- Proプランの状態
- 初回利用状態
- 通知の有効・無効
- テーマ設定
- その他、本アプリの表示や動作に必要な設定

### 2.7 デバイス情報

本アプリの動作確認、不具合対応、機能改善のため、デバイスの種類、OSバージョン、アプリバージョン等の情報を利用する場合があります。

---

## 3. 情報の利用目的

取得または保存した情報は、以下の目的で利用します。

1. 本アプリの提供、運営、機能実行のため
2. SSH接続設定、tmux設定、スニペット、Inboxを保存・表示するため
3. AI判断依頼の通知、承認、却下等の操作を提供するため
4. Proプラン等のアプリ内機能を提供するため
5. ユーザー設定を保存し、アプリ体験を改善するため
6. 不具合修正、品質改善、カスタマーサポートのため
7. 法令または利用規約に基づく対応のため

---

## 4. 情報の保存と管理

### 4.1 ローカル保存

本アプリで作成された接続設定、tmux設定、スニペット、Inbox、アプリ設定等のデータは、主にユーザーのデバイス内に保存されます。

### 4.2 外部サーバーへの送信

当社は、本アプリで保存されたSSH接続設定、スニペット、AI判断依頼の内容を、当社が管理する外部サーバーへ送信することを目的として収集しません。

ただし、本アプリの機能上、ユーザーが指定したSSHホスト、外部サービス、OSの通知基盤、アプリストア決済基盤等との通信が発生する場合があります。

### 4.3 バックアップ

OSまたはデバイスの設定により、アプリデータがiCloud、Googleバックアップ、端末バックアップ等の対象になる場合があります。これらのバックアップは、各プラットフォーム提供者の設定およびプライバシーポリシーに従って管理されます。

---

## 5. 第三者サービスの利用

本アプリは、以下の第三者サービスまたはプラットフォーム機能を利用する場合があります。

### 5.1 Apple App Store / Google Play

アプリの配信、アップデート、購入管理、返金処理等のため、AppleまたはGoogleのサービスが利用されます。決済情報は各プラットフォーム提供者が管理し、当社は購入状態の確認に必要な情報のみを受け取る場合があります。

- Apple プライバシーポリシー: https://www.apple.com/legal/privacy/
- Google プライバシーポリシー: https://policies.google.com/privacy

### 5.2 通知サービス

通知機能を利用する場合、Apple Push Notification service（APNs）またはFirebase Cloud Messaging（FCM）等、OSやプラットフォームが提供する通知基盤が利用される場合があります。

### 5.3 SSH接続先およびユーザー指定の外部サービス

ユーザーが登録したSSHホスト、起動コマンド、AIツール、その他の外部サービスとの通信は、ユーザーの操作および設定に基づいて行われます。接続先でのデータ処理は、各接続先またはサービス提供者の規約およびプライバシーポリシーに従います。

---

## 6. 第三者提供

当社は、以下の場合を除き、ユーザーの個人情報を第三者に提供しません。

1. ユーザーの同意がある場合
2. 法令に基づく場合
3. 人の生命、身体または財産の保護のために必要な場合
4. 本アプリの提供に必要な範囲で、プラットフォーム提供者、通知サービス、決済サービス等を利用する場合

---

## 7. データの削除

ユーザーは、本アプリ内で保存した接続設定、スニペット、Inbox情報等を削除できます。また、本アプリをアンインストールすることで、通常、デバイス内に保存された本アプリのデータは削除されます。

バックアップに保存されたデータの削除については、各OSまたはプラットフォームの設定をご確認ください。

---

## 8. ユーザーの権利

ユーザーは、ご自身の情報について、閲覧、訂正、削除、利用停止等を求めることができます。本アプリ内で操作できない情報に関するご請求やお問い合わせは、下記のお問い合わせ先までご連絡ください。

---

## 9. セキュリティ

当社は、ユーザー情報の漏えい、滅失、毀損等を防止するため、合理的な安全管理措置を講じます。

ただし、インターネット通信、端末内保存、外部サービスとの接続には完全な安全性を保証できない性質があります。SSH接続情報、認証情報、コマンド内容等の管理には十分ご注意ください。

---

## 10. 13歳未満の子どもについて

本アプリは、13歳未満の子どもを主な対象としていません。当社は、13歳未満の子どもから意図的に個人情報を取得することはありません。

保護者の方が、お子様が当社に個人情報を提供したことにお気づきの場合は、下記のお問い合わせ先までご連絡ください。

---

## 11. 国際的なデータ転送

本アプリは、日本国内のユーザーを主な対象としています。ただし、アプリストア、通知サービス、決済サービス、ユーザーが指定したSSH接続先または外部サービスによっては、情報が国外で処理される場合があります。

---

## 12. プライバシーポリシーの変更

当社は、必要に応じて本プライバシーポリシーを変更することがあります。重要な変更がある場合は、本アプリ内または公開ページ上で通知します。

変更後のプライバシーポリシーは、公開された時点で効力を生じます。

最終更新日: 2026年6月10日

---

## 13. お問い合わせ

本プライバシーポリシーに関するご質問、ご意見、または個人情報に関するご請求については、以下までご連絡ください。

**事業者**: 横川貴一  
**メールアドレス**: yok1012ichi@gmail.com  
**アプリ名**: AI Terminal

---

## 14. 準拠法と管轄裁判所

本プライバシーポリシーは、日本法に準拠し、解釈されるものとします。本プライバシーポリシーに関連する紛争については、東京地方裁判所を第一審の専属的合意管轄裁判所とします。

---

# Privacy Policy

## Business Information

Takaichi Yokokawa  
yok1012ichi@gmail.com

---

## 1. Introduction

Takaichi Yokokawa ("we," "us," or "our") provides the smartphone application "AI Terminal" (the "App"). This Privacy Policy explains how information is collected, used, stored, and managed in connection with the App.

By using the App, you agree to this Privacy Policy.

---

## 2. Information We Collect

The App may collect or store the following information to provide its features.

### 2.1 SSH Connection Settings

- Connection label
- Host name or IP address
- Port number
- Username
- Authentication method, such as SSH key, password, or agent
- Hints or reference information related to credentials
- Display color for each connection
- Created and updated timestamps

The App stores this information to help you manage SSH connections. If you enter sensitive information such as passwords or private keys, you are responsible for managing that information appropriately.

### 2.2 tmux Settings

- Whether tmux auto-attach is enabled
- Session name
- Window name
- Startup command
- Default tmux preset

### 2.3 Snippet Information

- Snippet title
- Command text
- Category, such as Claude, Git, tmux, or custom
- Display information related to Pro features

### 2.4 AI Judgment Requests and Inbox Information

- Confirmation requests from AI tools
- Related connection label
- Details of the request
- Created timestamp
- Status, such as approved, rejected, or pending

### 2.5 Notification Settings and Notification-Related Information

The App may send notifications when an AI tool is waiting for your decision. If notifications are enabled, the App uses the OS notification permission status, notification settings, and information necessary to display the notification.

### 2.6 App Settings

- Pro plan status
- Onboarding status
- Notification preferences
- Theme settings
- Other settings necessary for App display or behavior

### 2.7 Device Information

The App may use information such as device type, OS version, and App version for operation checks, troubleshooting, and feature improvements.

---

## 3. Purpose of Use

We use collected or stored information for the following purposes:

1. To provide, operate, and execute App features
2. To save and display SSH connection settings, tmux settings, snippets, and Inbox items
3. To provide AI judgment notifications and approval or rejection actions
4. To provide Pro plan and other in-app features
5. To save user preferences and improve the App experience
6. To fix bugs, improve quality, and provide customer support
7. To respond to legal requirements or terms-based matters

---

## 4. Storage and Management

### 4.1 Local Storage

Connection settings, tmux settings, snippets, Inbox items, App settings, and similar data created in the App are primarily stored on your device.

### 4.2 External Server Transmission

We do not collect SSH connection settings, snippets, or AI judgment request contents for the purpose of transmitting them to external servers managed by us.

However, depending on App functionality, communication may occur with SSH hosts specified by you, external services, OS notification infrastructure, app store payment systems, and similar services.

### 4.3 Backups

Depending on OS or device settings, App data may be included in iCloud, Google backups, device backups, or similar backup services. Such backups are managed according to the settings and privacy policies of the relevant platform providers.

---

## 5. Third-Party Services

The App may use the following third-party services or platform features.

### 5.1 Apple App Store / Google Play

Apple or Google services may be used for app distribution, updates, purchase management, refunds, and related processes. Payment information is managed by the relevant platform provider, and we may receive only the information necessary to verify purchase status.

- Apple Privacy Policy: https://www.apple.com/legal/privacy/
- Google Privacy Policy: https://policies.google.com/privacy

### 5.2 Notification Services

If notifications are enabled, notification infrastructure provided by the OS or platform, such as Apple Push Notification service (APNs) or Firebase Cloud Messaging (FCM), may be used.

### 5.3 SSH Hosts and User-Specified External Services

Communication with SSH hosts, startup commands, AI tools, and other external services specified by you is performed based on your actions and settings. Data processing at those destinations is governed by the terms and privacy policies of each destination or service provider.

---

## 6. Third-Party Disclosure

We do not disclose your personal information to third parties except in the following cases:

1. When we have your consent
2. When required by law
3. When necessary to protect a person's life, body, or property
4. When using platform providers, notification services, payment services, or similar services to the extent necessary to provide the App

---

## 7. Data Deletion

You can delete saved connection settings, snippets, Inbox information, and similar data in the App. Uninstalling the App will usually delete the App data stored on your device.

For data stored in backups, please check the settings of the relevant OS or platform.

---

## 8. Your Rights

You may request access to, correction of, deletion of, or suspension of use of your information. For requests or inquiries that cannot be handled within the App, please contact us using the contact information below.

---

## 9. Security

We take reasonable security measures to prevent leakage, loss, or damage of user information.

However, no method of Internet communication, device storage, or connection to external services can be guaranteed to be completely secure. Please carefully manage SSH connection information, credentials, command contents, and similar information.

---

## 10. Children Under 13

The App is not primarily intended for children under 13 years of age. We do not knowingly collect personal information from children under 13.

If you are a parent or guardian and become aware that your child has provided us with personal information, please contact us using the contact information below.

---

## 11. International Data Transfers

The App primarily targets users in Japan. However, depending on app stores, notification services, payment services, SSH hosts specified by you, or external services, information may be processed outside Japan.

---

## 12. Changes to This Privacy Policy

We may update this Privacy Policy as necessary. If there are significant changes, we will notify you within the App or on the public page.

The updated Privacy Policy becomes effective when published.

Last Updated: June 10, 2026

---

## 13. Contact

For questions, comments, or requests regarding this Privacy Policy or your personal information, please contact:

**Business**: Takaichi Yokokawa  
**Email**: yok1012ichi@gmail.com  
**App Name**: AI Terminal

---

## 14. Governing Law and Jurisdiction

This Privacy Policy is governed by and construed in accordance with Japanese law. Any disputes relating to this Privacy Policy shall be subject to the exclusive jurisdiction of the Tokyo District Court as the court of first instance.

---

© 2026 Takaichi Yokokawa. All rights reserved.
