FROM quay.io/sampandey001/secktor
RUN git clone https://github.com/saviya55/Saviya-Md /root/saviya55
WORKDIR /root/saviya55/
RUN npm install npm@latest
RUN npm install
EXPOSE 8000
CMD ["npm", "start"]
