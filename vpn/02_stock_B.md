----------------------------
# Basic knowlage

- 5分でわかるVPN
http://www.atmarkit.co.jp/ait/articles/0204/27/news003.html

- VPN基礎 history
http://biz.freebit.com/service/column/vpnbasic00.html

----------------------------
# solution

## Setting/MTU

- pmtudブラックホール/　数分〜5分おきにVPNが切断されてしまう原因と解決方法
http://geppeivpn.asia/2015/04/30/1709.html

    ICMP on,off

- pingでMTUサイズを調査する
http://www.atmarkit.co.jp/ait/articles/0512/17/news017.html

- Pingコマンド（Windows端末）でMTU調査
http://www.checksite.jp/ping-mtu-windows/


- 拠点間インターネットVPN （NAT超え）に関する整理
http://www.checksite.jp/about-internetvpn-ipsec-over-nat/


mtu 延長戦

ルーターのＭＴＵとWINDOWSのMTUの関係
https://oshiete.goo.ne.jp/qa/7820030.html

速度低下の原因と対策
http://mroom.xii.jp/bb/mtu.html


## change protocol?

------------

暗号化無し
バッファローPPTPサーバーへの接続が頻繁に切れる場合の回避方法2012/10/24 02:00（1年以上前）
http://bbs.kakaku.com/bbs/J0000003026/SortID=15244182/


isp（プロバイダー）問題
ネットワークが不安定になる原因がわかりません/2006
http://q.hatena.ne.jp/1158284964


mtu調整が何故必要か？　
VPNサービスの通信速度が遅い。または接続してもすぐに切れてしまいます。
https://faq.interlink.or.jp/faq2/View/wcDisplayContent.aspx?id=199


-------------
## router

中国でVPNがブチブチ切れる。VPNが切断されてしまう原因について
http://ameblo.jp/geppeivpn/entry-12100183312.html

YAMAHAのRTX1200:VPN環境で閲覧できないWEBサイトの原因は、MTU...
http://jehupc.exblog.jp/21558500/

ルーターの対処方法/ルーターの設定に関する解決方法/VPN接続ができない
http://jp.yamaha.com/products/network/solution/trouble_shooting/ts_router/


ipsec 利用時

VPN接続が5分程で切れてしまいます/port 開放
http://detail.chiebukuro.yahoo.co.jp/qa/question_detail/q11110412951

他
L2TP/IPSecのルータのポート開放で検索

------------
## power play / 自動接続、空パケット送信

[Mac OSX] VPNが頻繁に切断されてしまう時の対処方法
http://blog.odoruinu.net/2014/11/16/mac-osx-vpn-solution-for-problem-disconnecting-from-vpn/

------------

## OS/windows  
- VPN接続で２～３分経過すると、セッションが切断される
http://www.tegos.co.jp/blog/vpn%E6%8E%A5%E7%B6%9A%E3%81%A7%EF%BC%92%EF%BD%9E%EF%BC%93%E5%88%86%E7%B5%8C%E9%81%8E%E3%81%99%E3%82%8B%E3%81%A8%E3%80%81%E3%82%BB%E3%83%83%E3%82%B7%E3%83%A7%E3%83%B3%E3%81%8C%E5%88%87%E6%96%AD/

- netsh補足/［Windows 7編］ネットワーク設定を標準で使ってはいけない
http://itpro.nikkeibp.co.jp/article/COLUMN/20100824/351391/?rt=nocnt


------------
## aws vpn

ポリシーベースの VPN を使用しているときに AWS VPN エンドポイントへの接続が不安定になる問題を解決する方法を教えてください。
https://aws.amazon.com/jp/premiumsupport/knowledge-center/vpn-connection-instability/

------------
## other 
- VPN
http://program.sagasite.info/wiki/index.php?VPN

- VPNパススルー
http://program.sagasite.info/wiki/index.php?VPN%E3%83%91%E3%82%B9%E3%82%B9%E3%83%AB%E3%83%BC

- NATトラバーサル
http://program.sagasite.info/wiki/index.php?NAT%E3%83%88%E3%83%A9%E3%83%90%E3%83%BC%E3%82%B5%E3%83%AB


- トンネリング
http://program.sagasite.info/wiki/index.php?%E3%83%88%E3%83%B3%E3%83%8D%E3%83%AA%E3%83%B3%E3%82%B0

- IPsec と SSL / TLS との比較
http://www.kanadas.com/investigation-j/2007/11/ipsec_ssltls.html

- TCP/IP - ICMP
http://www.infraexpert.com/study/tcpip4.html

---------------------
# supplement

- VPN接続はできるがイントラ閲覧ができない
http://www.atmarkit.co.jp/bbs/phpBB/viewtopic.php?topic=17426&forum=11

- 未熟者が仮想プライベートゲートウェイを使ってVyOSとVPNを張るのに苦労した話
http://qiita.com/maaaato/items/fbeee7986c462a4cbf87

- OpenVPNで手軽にVPN構築
http://www.atmarkit.co.jp/flinux/special/openvpn/openvpna.html

