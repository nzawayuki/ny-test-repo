# ベースイメージを指定、脆弱性あり　https://hub.docker.com/_/alpine/tags?page=3
FROM alpine:3.17.5
 
# nginxのインストール
RUN apk update && apk add --no-cache nginx
 
# 設定ファイルの配布
ADD default.conf /etc/nginx/http.d/default.conf
 
# nginxnの実行
CMD nginx -g "daemon off;"
