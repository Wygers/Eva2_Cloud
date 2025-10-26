# Proyecto Docker - Nube Privada

## Comandos

- **Levantar el entorno**:  
  `docker compose up -d --build`

- **Verificar el estado de los contenedores**:  
  `docker compose ps`

- **Ver logs de un servicio**:  
  `docker compose logs -f <nombre_servicio>`

- **Detener los contenedores**:  
  `docker compose down`

- **Detener y eliminar contenedores + volúmenes**:  
  `docker compose down -v`

- **Acceder al contenedor web**:  
  `docker exec -it nube-web bash`

- **Acceder a la base de datos**:  
  `docker exec -it nube-db mariadb -uusuarioapp -pcontraapp -D empresa`
