# Node.js imajını kullan
FROM node

# Çalışma dizinini belirle
WORKDIR /workspace

RUN apt-get update && apt-get install -y git

# package.json dosyasını kopyala
COPY package.json /workspace/

# package.json varsa bağımlılıkları yükle
RUN npm install

RUN apt-get update

# Başlatılacak komut
CMD ["npm", "start"]
