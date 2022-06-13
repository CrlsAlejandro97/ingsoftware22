FROM node:16.15.0
WORKDIR /app
RUN cd /app
COPY . .
RUN npm i --no-audit --no-fund --no-optional
EXPOSE 3000
ENTRYPOINT ["npm", "run", "start"]