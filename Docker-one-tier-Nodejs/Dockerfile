FROM node:18-alpine
WORkDIR /app
COPY package.json /app
RUN npm install
COPY ./ /app
CMD ["node","index.js"]
#CMD ["npm","run","dev"]
