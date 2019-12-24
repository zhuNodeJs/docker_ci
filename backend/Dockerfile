FROM keymetrics/pm2:latest-alpine
WORKDIR /usr/src/app
ADD . /usr/src/app
RUN npm i
EXPOSE 3000
# PM2在docker中使用命令为pm2-docker
CMD ["pm2-runtime", "start", "process.yml"]
