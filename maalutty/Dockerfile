FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Starkbot90/MAALUTTY_V3 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Statkbot90/media

CMD ["node", "bot.js"]
