# Privacy Policy

*English summary: This application ("AIlin") is a personal automation tool operated solely by the domain owner for the owner's own use. It accesses Google Calendar only to create and delete events on the owner's own calendar. No user data is sold or shared with third parties. All data and OAuth tokens are stored locally on the owner's own server.*

Last updated: 2026-10-04

---

## アプリケーションについて

**AIlin** は、本ドメイン（gugucs.com）の管理者が**自身の用途専用**に運用する個人自動化ツールです。一般向けに提供するサービスではなく、利用者は管理者本人のみです。

## アクセスする Google データと利用目的

OAuth 認証を通じて、以下のスコープに基づき Google データへアクセスします。

| Scope | 目的 |
|---|---|
| `https://www.googleapis.com/auth/calendar.events` | 管理者自身の Googleカレンダーに予定を作成・削除するため |
| `https://www.googleapis.com/auth/calendar.readonly` | カレンダーの一覧を読み取り、登録先カレンダーを特定するため |

- アクセス対象は**管理者自身のカレンダーのみ**です。他のユーザーのデータにはアクセスしません
- カレンダー以外の Google データ（Gmail・Drive 等）にはアクセスしません

## データの取り扱い

- **外部への提供なし**: 取得したデータを第三者へ販売・提供・送信しません
- **ローカル保存**: メモ・予定データおよび OAuth トークンは、管理者が自宅で運用するサーバーのローカルディスクにのみ保存されます（トークンはパーミッション 0600）
- **AI 処理について**: 予定の抽出にあたり、**個人情報をマスク済みのテキストのみ**を外部の大規模言語モデルサービスへ送信します。画像・音声・生テキストを外部へ送信しません
- **ログ**: カレンダー登録・削除の履歴はローカルのログファイルに記録されます

## 権限の取り消し

管理者はいつでも Google アカウントの[サードパーティ アクセス設定](https://myaccount.google.com/permissions)から本アプリケーションの権限を取り消せます。取り消し後は即時にアクセスできなくなります。

## お問い合わせ

本ドメイン（gugucs.com）の管理者まで。Google Auth Platform のデベロッパー連絡先メールアドレスが管理者の連絡先です。

---

*Last updated: 2026-10-04*
