# Welcome to the MongoDB Training Notes

## Topics

* Mongodb Order Insert
* Basics
* Aggregation
* CRUD
* (Concern) Write Concern , Insert Concern
* Management
* MongoDB Security
* MongoDB Cluster (Sharding, Replicaset)
* Capped Collection
* Index
    * Write -: Write once
    * Read  -: It will happen again and again, so Read operation may slow down read performance, so we can increase Read Performance
    * db.person.createIndex("dob.age" : 1) , db.person.createIndex("dob.age": 1 , "gender" : 'male') #Composite Index

## Resources
* https://www.mongodb.com/docs/manual/tutorial/getting-started/
* https://www.mongodb.com/docs/manual/reference/method/db.collection.createIndex/
