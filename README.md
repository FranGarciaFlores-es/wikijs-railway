# Wiki.js en Railway

Este repositorio contiene la configuración mínima para desplegar Wiki.js en Railway sin tarjeta de crédito.

## 🚀 Pasos para desplegar

1. Sube este repo a tu GitHub.
2. En Railway → New Project → Deploy from GitHub.
3. Añade un servicio PostgreSQL:
   - Add → Database → PostgreSQL.
4. En el servicio Wiki.js añade estas variables de entorno:

- DB_TYPE=postgres
- DB_HOST=${PGHOST}
- DB_PORT=${PGPORT}
- DB_USER=${PGUSER}
- DB_PASS=${PGPASSWORD}
- DB_NAME=${PGDATABASE}

5. Configura el puerto:
   - Service Port: **3000**

6. Railway generará una URL pública.
7. Entra y completa la instalación de Wiki.js.

