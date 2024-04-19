# Conectando a tu contenedor
``` sh
docker-compose exec mongodb bash
```

# Conectando con mongosh
``` sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
mongosh "mongodb+srv://josephadmin:josephadmin123@cluster0.sq5ry8y.mongodb.net/"
```

``` sh
show dbs
show collections
```

``` sh
use ("platzi_store")
db.products.find()
```