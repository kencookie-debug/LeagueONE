ラグビーリーグONE Androidアプリ用プロジェクト

このZIPは、Androidに直接インストールするAPKをクラウド上で作るためのプロジェクトです。
APKそのものではありません。

【スマホだけでビルドする流れ】
1. GitHubにログインし、新しいリポジトリを作成します（例: rugby-leagueone-app）。
2. このZIPを解凍し、中のファイルとフォルダをリポジトリにアップロードします。
   .github フォルダも含めてください。
3. GitHubのリポジトリ画面で「Actions」を開きます。
4. 「Build Android APK」を選び、「Run workflow」を押します。
5. ビルド完了後、実行結果を開き、Artifactsの rugby-leagueone-debug-apk をダウンロードします。
6. ZIPを解凍し、中の app-debug.apk を開いてインストールします。

初回はGitHubのActions利用確認やAndroid側の「不明なアプリのインストール許可」が必要な場合があります。
APKはデバッグ署名版です。Playストア公開用の署名済みリリース版ではありません。

アプリ内データはWebViewのローカルストレージに保存されます。アプリのデータ消去やアンインストールで消える可能性があります。
