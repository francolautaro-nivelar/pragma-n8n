# Pragma — n8n Self-hosted

Instancia de n8n para el sistema Pragma. Corre en Railway con base de datos en Supabase.

## Setup en Railway

1. Crear repo en GitHub con estos archivos
2. Conectar repo en Railway → New Project → Deploy from GitHub
3. Agregar variables de entorno (ver `.env.example`)
4. Railway hace el build automático con el Dockerfile
5. Una vez deployado, copiar la URL generada y ponerla en `N8N_HOST`

## Variables de entorno requeridas

Ver `.env.example` para la lista completa con instrucciones.

## Acceso

Una vez deployado, entrar a `https://tu-proyecto.up.railway.app`
- Usuario: el que pusiste en `N8N_BASIC_AUTH_USER`
- Password: el que pusiste en `N8N_BASIC_AUTH_PASSWORD`

## Zona horaria

Configurado para `America/Argentina/Buenos_Aires` por defecto.
