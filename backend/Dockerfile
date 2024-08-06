FROM node:20
ENV DB_HOST=mysql \
    DB_USER=expense \
    DB_PWD=Expense@1 \
    DB_DATABASE=transactions

RUN mkdir /opt/server
RUN useradd expense
RUN chown expense:expense -R /opt/server
WORKDIR /opt/server
COPY package.json .
COPY *.js ./
RUN npm install
USER expense
EXPOSE 8080
CMD ["node","index.js"]
