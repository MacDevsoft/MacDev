# Usa una imagen base oficial de Node.js
FROM node:18  

# Establece el directorio de trabajo dentro del contenedor
WORKDIR /app  

# Copia los archivos necesarios y instala dependencias
COPY package.json ./
RUN npm install  

# Copia todo el código al contenedor
COPY . .  

# Expone el puerto en el que corre la app
EXPOSE 3000  

# Comando para iniciar la aplicación
CMD ["npm", "start"]
