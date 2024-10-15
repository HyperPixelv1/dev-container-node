# Node.js imajını kullan
FROM node:8

# Çalışma dizinini belirle
WORKDIR /workspace

# package.json dosyasını kopyala
COPY package.json /workspace/

# package.json varsa bağımlılıkları yükle
RUN npm install

# Başlatılacak komut
CMD ["npm", "start"]
