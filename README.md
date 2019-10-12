# nginx-static-mock
----

1. /data/nginx/json/ に適当なjsonファイルを配置
2. http://<IP>:10080/mock/<jsonファイル名> で任意のJSONを返却できる.

Nginxでは静的ファイル返却に対してPOSTを許可することができないらしいのであんま役立たないわ
参考：https://qiita.com/toris-birds/items/1e99e2be0e337253fe83
