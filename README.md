# Minecraft Server Starter — Windows版

Minecraft Server Starterのインストーラーと、アプリ内更新用ファイルを配布しています。

[最新版をダウンロード](https://github.com/roqy3/MinecraftServerStarter-updates/releases/latest)

## インストール・更新

1. サーバーを正常停止し、サーバー全体のバックアップを作成します。
2. 旧アプリを閉じ、新しいインストーラーを実行します。事前のアンインストールは不要です。
3. サーバー一覧と従来のワールドを確認します。

同じWindowsユーザーで更新する場合、ワールド・Mod・プレイヤーデータ・設定は引き継がれます。
アンインストール時の「アプリデータを削除」に相当する項目は選ばないでください。

v1.4.2以前からは、v1.4.3を手動で導入してください。
v1.4.3以降は「運用センター → アプリ更新」から今後の新バージョンに更新できます。
サーバーやバックアップなどの処理をすべて停止してから更新を実行してください。

## 配布ファイル

- `MinecraftServerStarter_<version>_x64-setup.exe`：Windows x64インストーラー
- `.exe.sig`：更新用の公開署名
- `latest.json`：アプリ内更新情報
- `SHA256SUMS.txt`：インストーラーのSHA256
- `MIGRATION.md` / `UPDATING.md` / `README.md`：移行・更新の手順

アプリ内更新では更新ファイルの署名と署名されたバージョンを検証します。
Windows Authenticodeのコード署名は未設定です。

このリポジトリは配布専用です。ソースコードと署名用の秘密鍵は含みません。
