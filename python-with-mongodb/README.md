# Accessing Database using Python
----
## 1. No-SQL DB - MongoDB

----
##### Basic Command for MongoDB, for more information (MongoDB Documentation)[https://docs.mongodb.com/guides/]
Open Command Prompt --> Run `"C:\Program Files\MongoDB\Server\4.2\bin"`
1. Create Database `use Employee`
2. Insert 1 JSON Document to the Employee Database
```
db.collection.insertOne({"_id":"w1790106", "firstname":"Rathnayaka","lastname":"Bandara"})
```
3. Insert Many JSON Document to the Employee Database
```
db.collection.insertMany([{"_id":"w1790401", "firstname":"Viraj","lastname":"Bandara"},{"_id":"w1232322","firstname":"Lakshitha", "lastname":"Bandara"}])
```
4. Find all the existing JSON Documents
```
db.collection.find({})
```
5. Find specific JSON Document
```
db.collection.find({"firstname":"Lakshitha"})
```

## 2. SQL Database
