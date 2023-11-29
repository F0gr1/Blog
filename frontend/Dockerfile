# ベースイメージを指定
FROM node:20.9-alpine

# 作業ディレクトリを設定
WORKDIR /usr/src/app

# 依存関係をコピー
COPY workspace ./


# 依存関係をインストール
RUN npm install

# アプリケーションをビルド
RUN npm run build

# アプリケーションを実行
CMD ["npm", "start"]
