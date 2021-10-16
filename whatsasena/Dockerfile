FROM fusuf/whatsasena:latest

RUN git clone https://github.com/cyberromeo124/CYBER-ROMEO/root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
