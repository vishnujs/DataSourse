# Select/Find
For projecting only the column name
```
db.getCollection('CollectionName').find({},{columnName:1})
```
# Queries
For finding a matching valus in a list of objects use the following command
```
db.getCollection('CollectionName').find({images:{$elemMatch:{imageName:"imageName"}}})
```
where CollectionName is the name of the collection containing a list images where one of the object is imageName

