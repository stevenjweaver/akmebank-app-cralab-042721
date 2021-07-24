FROM node:12.22.3-buster-slim

WORKDIR "/tools"
ADD . /tools
RUN  npm install
ENV PATH="/tools:${PATH}"

ENTRYPOINT ["accounts"]

