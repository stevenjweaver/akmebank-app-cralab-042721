FROM node:erbium-buster-slim

WORKDIR "/tools"
ADD . /tools
RUN  npm install
ENV PATH="/tools:${PATH}"

ENTRYPOINT ["accounts"]

