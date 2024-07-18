FROM node:20-alpine

WORKDIR /app

# react-app ディレクトリ内のファイルをコピー
COPY package.json package-lock.json ./
RUN npm install

COPY . .

EXPOSE 3000

CMD ["npm", "start"]