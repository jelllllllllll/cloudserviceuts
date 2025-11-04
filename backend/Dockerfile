# Gunakan image Node.js resmi
FROM node:18

# Set working directory
WORKDIR /app

# Copy file package.json dan package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy semua file project ke dalam container
COPY . .

# Jalankan server
CMD ["npm", "start"]

# Container akan listen ke port 5000
EXPOSE 5000
