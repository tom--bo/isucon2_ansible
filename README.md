# isucon2環境作成


## ざっくり環境（互換性等で問題会った時用のメモ)
-  python 2.7.6
-  ansible 1.8.2
-  host: mac 
-  target: Google Cloud Platform / Centos6.6

- 手動でSELinux切って再起動w
/etc/sysconfig/selinux
SELINUX=disabled

## 今後のTODO

-  ISUCON2の環境設定
-  ベンチマーク動かす
-  varnishとかとか

## Done

-  中止：LAMP環境作る
-  gcpで動くようにする
-  nginx入れる


## 参考等

- 序盤は以下、ansibleチュートリアル参考。
- http://yteraoka.github.io/ansible-tutorial/
- Google Cloud Platformへのsshアクセス
- http://qiita.com/NewGyu/items/3a65e837519297951e79

hello!hello!

