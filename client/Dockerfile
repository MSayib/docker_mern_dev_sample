FROM node:21.5.0
COPY . .
RUN npm install
EXPOSE 3000
RUN npm run build
CMD ["npm", "run", "start"]