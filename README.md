# AspnetCoreMicroservices
AspnetCoreMicroservices

#command docker
#show list container__
docker ps
#run image mongodb__
1. docker pull mongo \
2. docker run -d -p 27017:27017 --name shopping-mongo mongo \
#check log mongo__
docker logs -f shopping-mongo \
#run command exec mongo__
docker exec -it shopping-mongo /bin/bash \
#mongo cmd basic 
ls
mongo
show dbs
use CatalogDb
db.createCollection('Products')
db.Products.find({}).pretty()

db.Products.remove({})
show databases
show collections
db.Products.find({}).pretty()
#Package Management Console \
Update-package -ProjectName Catalog.API