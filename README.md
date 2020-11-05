# Nginx Manager + letsencrypt auto + Docker + Docker Compose

## Utilidad

Generar proxys para poder obtener diferentes sitios con certificados SSL autorenovables.
Configurar un solo sitio en segundos, y que este esté protegido por SSL de letsencrypt y que se renueve automáticamente.

## Cómo instalar

- En el servidor host instalar Docker + Docker Compose + git.
- Clonar este repo. git clone ....
- Ejecutar la siguiente línea: docker-compose up -d
- Una vez que se haya ejecutado, visitar el sitio en el puerto 81: <IP PUBLICA>:81
- usuario: *admin@example.com* pass: *changeme*
