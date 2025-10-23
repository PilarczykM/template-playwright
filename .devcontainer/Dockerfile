FROM mcr.microsoft.com/playwright

WORKDIR /workspace

COPY package*.json /

RUN if [ -f package.json ]; then npm install; fi

COPY . .
