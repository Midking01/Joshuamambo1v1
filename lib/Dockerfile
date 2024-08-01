FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/MidKing01/Joshuamambo1v1 /root/MidKing01
WORKDIR /root/MidKing01/
RUN npm install npm@latest
RUN yarn install --network-concurrency 1
EXPOSE 8000
CMD ["npm", "start"]
