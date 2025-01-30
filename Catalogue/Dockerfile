FROM node:18
EXPOSE 8080
WORKDIR /opt/server/
COPY package.json server.js /opt/server/
ENV MONGO=true
RUN npm install
CMD ["node", "server.js"]