iBeacon_Demo
============
【ヒカ☆ラボ】あなたのMacがあっという間にBeacon端末に変身！～2015年必ずクル「iBeacon」を1から10まで～

　

2014.11.25 イベント後

以下、修正・追加実装を行いました。

・スライドで紹介したCLLocationManagerDelegateのメソッドをすべて実装しました

・モニタリング、レンジングエラーをダイアログで表示するようにしました

・初回インストール時に、位置情報の許可を求めるダイアログ表示を実装しました

　
#### 【iOS8】アプリ作成時のポイント
iOS8では位置情報を使用する際、使用理由の表示が必須となりました。

iBeaconでは、アプリがバックグラウンドにある際もモニタリングを続けなければならないため「常に許可」が必要です。

使用理由は、"Info.plist"に記載します。

新たに"NSLocationAlwaysUsageDescription"という項目を追加して、使用理由を記入してください。

