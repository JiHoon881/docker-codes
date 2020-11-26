FROM node:10

WORKDIR /usr/src/app

COPY package.json ./

RUN npm install

COPY ./ ./

CMD ["node", "server.js"]

# 맥에서
# -v $(pwd):/usr/src/app
# 윈도우에서
# -v %cd%:/usr/src/app
# 이런 식으로 다르게 $(pwd) => %cd% 이렇게 다르게 사용해주시면 됩니다 