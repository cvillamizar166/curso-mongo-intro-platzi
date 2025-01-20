# Connectarse a la terminal de mongo por medio del contenedor que ya lo tiene

``` sh
docker-compose exec mongodb bash
```

# Connectarse a mongosh

``` sh
mongosh "mongodb://root:root1235@localhost:27017/?tls=false"
```

# Comandos dentro del mongo sh

``` sh
show dbs
show collections
```

``` sh
use("platzi_store")

db.products.find()
```