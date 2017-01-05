# check sheet

# Index
- 1 basic trouble / 基本的なトラブルの種類
- 2 prepare, reserch / 準備、リサーチ


---------------

# 1 basic trouble / 基本的なトラブルの種類

## 1-1 case / ケース
- case A : don't connection / vpn接続自体が出来ない場合
- case B : connection ok.but not stable / vpn接続は出来るが安定していない。切れる。

## A-1 vpn接続自体が出来ない場合

    具体的な事例：02_stock_A.md

## B-1 general cause / 一般的な原因

- setting miss / 設定ミス

- protocol compatibility / プロトコルと相性

- network transfer volume / ネットワーク転送量
パケット単位(mtu) 〜　プロバイダー、回線単位

- other / その他


## B-2 general solution/ 一般的な解決策

    具体的な事例：02_stock_B.md

- router等特定の機器を使用している場合はサポートTELも有り
router imcp check / データ分割の有効、無効チェック


- protocol change / プロトコルを変える

ipseq,pptp,l2tp,ger

- firewall

- network quolity check/ ネットワーク品質、転送量等のチェック


mtu設定を変える

回線を変える



- power play / 強制的な対策

暗号化を使わない

切断される通信の持続、空パケットを定期的に送る。


- インフラ業者



---------------

# 2 prepare, reserch / 準備、リサーチ

please check network configration & environment. / ネットワーク構成、環境の確認

- 2-1 server side
- 2-2 client side
- 2-3 server side to inside (or broad network access via vps.)


## 2-1 server side / vpnサーバー側

- Vpnソフト(ハード):
- Router/ルーター:
- NetLine/ネット回線 :
leased line,ip-vpn,internet-vpn(ip-seq,ssl),entry-vpn?

- Provider/プロバイダー:


## 2-2 client side / vpnクライアント側

- Provider/プロバイダー :
- NetLine/ネット回線 :
- Router/ルーター :
- Hub/ハブ :

    ※ スマホや外出先PCのから接続だと上記を除外する場合も

- Line/LAN 有線・無線 :
- PC :
- OS :
- Software :
- Setting :

and trouble state check. / トラブル時の状態を報告してもらう。


## 2-3 server side to inside (or broad network access via vps.) / vpnサーバー以降

- example (ip limited for web app or server)

? difirent mtu size trouble?

---------------








