## Connect to conteiner 
docker compose exec  mongodb bash

## Connect with mongosh
mongosh "mongodb://root:root123@localhost:27017/"

show dbs
show collections

use("platzi_store")

db.products.find()
