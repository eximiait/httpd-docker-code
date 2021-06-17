# httpd-docker-code

## Construir imagen

```bash
docker build . -t httpd-docker
```
 
## Ejecutar imagen

```bash
docker run --name httpd-docker -p 80:80 httpd-docker
``` 

## Probar imagen

Acceder a http://localhost