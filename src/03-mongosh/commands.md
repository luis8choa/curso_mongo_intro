## Connect to container

```sh
docker-compose exec mongodb bash
```
Entramos al contenedor, ejecutamos el servicio mongodb y ejecutamos la terminal tipo bash.

Esa es la forma de conectarnos a un servicio que tenemos en docker

## Connect with mongosh

Si ese servicio tiene mongodb
```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"

mongosh "mongodb+srv://gerita1999:Luis8choa@mongodb101.wlbapqs.mongodb.net/"
```
Conectarnos a la url de conexion (la url nos la dara mongo)

1. base de datos

```sh
show dbs
show collections
```

```sh
use("platzi_store")
db.products.find()
```