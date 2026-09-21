# Atlas大学｜保健室

朝の定点観測を見返すための閲覧用Webアプリ。

- 正本: Notion MODB
- UI: このPrivate repository
- 認証/閲覧用ミラー: Supabase Auth + PostgreSQL/RLS
- 機密キーやNotion tokenはフロントエンドへ置かない

## Functional Prototype
ログイン、今日/7/30/90日/全期間、睡眠・血圧・心拍・HRV・自律神経スコア、本人のことば、推移グラフ。

## Next gate
Supabase側に morning_observations と単一ユーザーAuth、厳格なRLSを作成し、サーバー側Notion→Supabase同期を接続してからデプロイする。
