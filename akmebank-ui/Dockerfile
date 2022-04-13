FROM node:12.22.11-buster-slim

WORKDIR "/app"
ADD . /app
RUN  npm install
ENV PATH="/app:${PATH}"

ENTRYPOINT ["npm","start"]

