# Course Collections

These files are meant to be used with the `mongoimport` tool, to import the files use the tool as follows:

`mongoimport -d cooker -c recipes recipes.json`

`mongoimport "mongodb://root:root.pwd@localhost:27017/?authSource=admin&readPreference=primary&ssl=false" --db cooker collections/examples.json`

`mongoimport "mongodb://root:root.pwd@localhost:27017/?authSource=admin&readPreference=primary&ssl=false" --db cooker collections/recipes.json`

`mongoimport "mongodb://root:root.pwd@localhost:27017/?authSource=admin&readPreference=primary&ssl=false" --db cooker collections/users.json`

If you need to import these collections via MongoDB Compass please use the versions in the [`compass`](compass) folder.

_Using MongoDb 4.4+? See [note](../#download-mongodb-database-tools-if-using-44) in README about `mongoimport`._
