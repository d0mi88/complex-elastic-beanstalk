FROM node:alpine
WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY . .

# Instead of npm run dev as in the Dockerfile.dev call the start-script defined in the package.json
CMD ["npm","run","start"]