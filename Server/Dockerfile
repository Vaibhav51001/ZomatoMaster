FROM node:alpine

WORKDIR /app
COPY ./package.json ./
RUN npm install
COPY . .

# ENV MONGO_URL=mongodb+srv://AdityaGusain:AdityaGusain@zomato-master.3flxm.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
# ENV GOOGLE_CLIENT_ID=340910053462-dndhpbkvukd5jg5rsglnu9d7i1son355.apps.googleusercontent.com
# ENV GOOGLE_CLIENT_SECRET=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
# ENV AWS_S3_ACCESS_KEY=AKIAS2KUM2FU4TJUJF7N
# ENV AWS_S3_SECRET_KEY=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

ENV MONGO_URL=mongodb+srv://KrVaibhav:6200028165@cluster0.hdzg7.mongodb.net/zomatoDataBase?retryWrites=true&w=majority

ENV GOOGLE_CLIENT_ID=221350151662-f6c5jjebb1ak9fqe3ev6jkbi3cd30jcj.apps.googleusercontent.com

ENV GOOGLE_CLIENT_SECRET=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

ENV AWS_S3_ACCESS_KEY=AKIAXCL7CU5KUSFKNZXJ

ENV AWS_S3_SECRET_KEY=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

ENV NODE_ENV=production

ENV PORT=4000



RUN npm run build

CMD ["npm", "run", "start"]