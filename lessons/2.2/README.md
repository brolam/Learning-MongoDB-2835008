# Using .find() to query Documents

The `find()` command is one of the most basic MongoDB commands and acts much like a SELECT statement in SQL. Learn how to use `find()` to query our recipe Documents and find specific recipes.

## Links

- [Query Documents](https://docs.mongodb.com/manual/tutorial/query-documents/)
- [db.collection.find()](https://docs.mongodb.com/manual/reference/method/db.collection.find/)

# Commands
- db.recipes.find({"title" : "Tacos"})
- db.recipes.find({"title" : "Tacos",  "cook_time" : 20}).pretty()
- db.recipes.find({"title" : "Tacos"}, {"title": 1})
- db.recipes.find({}, {"title": 1})
- db.recipes.find({"title": {$regex: /taco/i}}, {"title": 1})
