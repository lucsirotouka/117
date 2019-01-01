# 117
オンライン 117（時報・音声時計） [**` 開く `**](https://yuru4c.github.io/117/)

## 概要
ウェブブラウザで動作する時報です。  
読み込み時に『NICT インターネット時刻供給サービス』から時刻を取得します。

株式会社ユアネーム様の『オフライン 117』に模しています。

## 備考
発振音とアナウンスは、再生にユーザーの操作を要するブラウザがあるため、読み込み時には無効です。  
設定は、アドレスのハッシュへ保存されます。オフライン 117の引数と互換性があります。

新しいブラウザの機能を使用するため、正しく動作しないかもしれません。  
バックグラウンドになると、ブラウザの最適化により処理落ちすることがあります。

うるう秒に対応しています。時刻の補正時に、うるう秒の情報も取得します。  
発振音は、2012年以降の加入電話向け時報サービスと同じ方法で挿入します。削除時は1秒早めます。

## 注意
このプログラムは、コンピューターの時計が正しく進むことを前提としています。  
特に、時刻補正後に調整されたり、ずれたりすると正しい時刻は表示されません。

## リンク
* [日本標準時(JST)グループ](http://jjy.nict.go.jp/tsp/PubNtp/index.html)

+ ~~[オフライン117（時報・音声時計）](http://www.yourname.jp/soft/offline117.shtml)~~
