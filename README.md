
## Cliente Gateway 
El gateway es el punto de comunicación entre nuestros clientes y nuestros servicios.
Es el encargado de recibir las peticiones y enviarlas a los servicios
correspondinetes y devolver la respuesta al cliente.

## Dev
1. Clonar el repositorio
2. Instalar dependencias
3. Crear un archivo `.env` basado en el `env.template`
4. Tener levantados los microservicios que se van a consumir 
5. Levantar proyecto con `npm run start:dev`

## Nats
```
docker run -d --name nats-main -p 4222:4222 -p 8222:8222 nats
```