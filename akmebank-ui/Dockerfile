FROM node:12.22.7-buster-slim

WORKDIR "/app"
ADD . /app
RUN  npm install
ENV PATH="/app:${PATH}"

ENTRYPOINT ["npm","start"]

