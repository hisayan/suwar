# 諏訪テイクアウトマップ AR (beta)

## 利用方法

### 全データ (読み込みが遅い)
https://suwar.tomap.app

### それぞれの地域のみ（読み込みが速い） 

+ https://suwar.tomap.app?area=諏訪
+ https://suwar.tomap.app?area=茅野
+ https://suwar.tomap.app?area=岡谷
+ https://suwar.tomap.app?area=富士見・原村
+ https://suwar.tomap.app?area=下諏訪

## Demo

位置情報をシミュレート。

+ https://suwar.tomap.app?demo=茅野駅


## ローカルでテストする場合は

たとえば、こうして、Webサーバーを起動しておいて、

```
Python 2.7
$ python -m SimpleHTTPServer 8080

Python 3
$ python -m http.server 8080
```

カメラへのアクセス等に、https が必要だから serveo などを経由する

```
$ ssh -R 80:localhost:8080 serveo.net
```
