FROM node:alpine
WORKDIR "/app"
COPY ./package.json ./
RUN npm install
COPY . .
CMD ["npm","run","start"]

# We do not need hostname for worker and nginx as they
# are not called directly