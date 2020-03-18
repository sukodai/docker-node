# docker-node

node アプリを docker コンテナに入れる

ビルド  
`docker build -t sukodai/node-web-app .`

実行  
`docker run -p 49160:8080 -d sukodai/node-web-app`


### 参考
 [Node.js Web アプリケーションを Docker 化する](https://nodejs.org/ja/docs/guides/nodejs-docker-webapp/)
