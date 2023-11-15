FROM docker.io/library/node:18

WORKDIR /opt/bundler
COPY . .

RUN yarn && yarn preprocess
ENTRYPOINT ["yarn", "bundler"]
CMD []
