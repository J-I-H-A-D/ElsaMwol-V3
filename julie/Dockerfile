FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/J-I-H-A-D/ElsaMwol-V3 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/J-I-H-A-D/Media
RUN cp -R /root/Utils/* /root/WhatsAsenaDuplicated 
CMD ["node", "bot.js"]
