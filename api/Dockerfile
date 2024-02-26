# Pilih image yang akan digunakan
FROM node:21.5.0

# Set direktori didalam container nanti yang akan digunakan projectnya
WORKDIR .

# Copy semua dari direktori saat ini ke dalam container
COPY . .

# Install semua dependensi yang dibutuhkan
RUN npm install

# Expose port 3001
EXPOSE 3001

# Command yang akan dijalankan saat container dijalankan (tidak akan dijalankan saat container di build)
CMD ["npm", "run", "start"]