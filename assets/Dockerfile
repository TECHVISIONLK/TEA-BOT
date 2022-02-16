FROM blackamda/queenamdi:public

RUN git clone https://github.com/TECHVISIONLK/TEA-BOT /root/TEA-BOT
WORKDIR /root/TEA-BOT/
ENV TZ=Asia/Colombo
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "assets/module.js"]
