## AspnetCoreMicroservices


#### Docker Command

###### show list image
> docker ps

###### pull and run image mongodb
> docker pull mongo

> docker run -d -p 27017:27017 --name shopping-mongo mongo

###### check log and exec bash mongo

> docker logs -f shopping-mongo

> docker exec -it shopping-mongo /bin/bash

###### Mongo Command basic
> mongo

> show dbs

> use CatalogDb

> db.createCollection('Products')

> db.Products.find({}).pretty()

> db.Products.remove({})

> show databases

> show collections
> db.Products.find({}).pretty()

#### Package Management Console

> Update-package -ProjectName Catalog.API