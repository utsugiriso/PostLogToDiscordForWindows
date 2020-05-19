# PostLogToDiscordForWindows
ログファイルをtailして、正規表現でフィルターして、Discordにぶん投げるWindowsアプリ

## システム要件
* .NET Framework 4.7.2が動くこと
* Windows PowerShellが動くこと(バージョンとか互換とかは確認していません)

未だにPowerShell使わずにログをtailする方法がわからない...なお、FileSytemWatcherではいつものごとくうまくいかない模様

## 見た目

メッセージPrefixのところに上記のようなフォーマットでDiscordのユーザーIDをコピペするとメンションできます
