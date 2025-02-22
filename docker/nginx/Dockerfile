# ベースイメージを指定
FROM alpine:latest
 
# nginxのインストール
RUN apk update && apk add --no-cache nginx
 
# 設定ファイルの配布
ADD default.conf /etc/nginx/http.d/default.conf
 
# nginxnの実行
CMD nginx -g "daemon off;"
