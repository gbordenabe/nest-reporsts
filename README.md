# Ejecutar en Dev

1. Clonar el repositorio
2. Instalar dependencias `npm install`
3. Clonar `.env.template` y renombrar a `.env`
4. Levantar la base de datos `docker compose up -d`
5. Generar el prisma client `npmz prisma generate`
6. Ejecutar projecto `npm run start:dev`