FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/cybertest317/magenero /root/cybertest317
WORKDIR /root/cybertest317/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]

