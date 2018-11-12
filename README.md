1. All await statements should be surrounded by a try/catch block.
2. If a callback isn't provided, asynchronous methods in the Node driver will return a Promise.
3. To use the await keyword, the enclosing function must be marked async.
4. What do the methods find() and find_one() have in common? - They accept a query predicate. They are used to query documents in a collection. They accept a field projection.
5. Which of the following aggregation stages have equivalent cursor methods? - $sort, $skip, $limit.
6. What is true about the result object of an insert_one (InsertOneResult)? - It can tell us whether the operation was acknowledged by the server.It contains the _id of an inserted document.
7. Which of the following Write Concerns are valid in a 3-node replica set? - w: 0 ;  w: 1 ; w: majority
8. Which of the following are valid update operators in Pymongo? - $set, $push, $inc
9. Which of the following is true about deleting documents in Pymongo? - DeleteResult objects contain the number of deleted documents. delete_many() can delete any number of documents. delete_one() can only delete one document.
10. Which of the following Read Concerns are valid in a 3-node replica set?  - "majority", "local"
11. Which of the following is true about bulk writes? By default, bulk writes are ordered.Bulk writes decrease the effect of latency on overall operation time.
12. Which of the following are benefits of connection pooling? - A large influx of operations can be handled more quickly with a pool of existing connections. New operations can be serviced with pre-existing connections, so a new connection doesn't have to be created each time.
13. When should you set a wtimeout? When our application is using a Write Concern more durable than w: 1.
14. What of the following is true about Change Streams in Pymongo? - They can be used to log changes to a MongoDB collection. They output cursors, which contain change event documents. They accept pipelines, which can be used to filter output from the change stream.
