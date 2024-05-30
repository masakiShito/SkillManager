FROM node:21

WORKDIR /app

# パッケージファイルをコピー
COPY react-app/package.json react-app/package-lock.json* ./

# 依存関係をインストール
RUN npm install

# アプリケーションのソースをコピー
COPY react-app/ .

# アプリケーションを開始
CMD ["npm", "start"]