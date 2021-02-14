# Redis.





## Contents at a Glance.
* [About](#about)
* [Documentation.](#documentation)
* [Pros.](#pros)
* [Cons.](#cons)
* [In Memory Key-Value Store](#in-memory-key-value-store)
* [Optional Durability](#optional-durability)
* [Transport protocol](#transport-protocol)
* [Pub. Sub](#pub-sub)
* [Replication. Clustering.](#replication-clustering) 
* [Help](#help)





## About.





## Documentation.





## Pros.





## Cons.





## In Memory Key-Value Store
* Redis is Key-Value Store NoSQL Database
* Key is a string, value is pretty much anything
* Redis is in memory first
* Single threaded (except when durability is enabled)





## Optional Durability
* Journaling (append only log AOP)
* Snapshotting
* Both happen asynchronously in the background





## Transport protocol
* Uses TCP
* Request / response just like HTTP
* Message format is RESP (Redis Serialization Protocol)





## Pub. Sub
* Redis supports Publish subscribe model
* Switches to PUSH model in that case





## Replication. Clustering.
* Replication - One Leader many followers model
* Clustering - Shard data across multiple nodes
* Hybrid





## Help.
