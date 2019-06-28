
### Use cases

##### Voting. There is a set of authorised entities (e.g. people, device, organization) to take part into collective decisions making.  People go to trusted location and anonymously vote. Then ballot sent to centralised party. 
- Permissioned blockchain

##### Direct transactions without central athority - money (cash is anonymous)
-  Permissionless Distributed leger with a token (e.g. ETH or EOS blockchain) - cryptocurrency

##### Supply chain
- blockchain

##### Audit log - building audit functionality with relational databases is time-consuming and prone to human error. It requires custom development, and since relational databases are not inherently immutable, any unintended changes to the data are hard to track and verify.
- blockchain

##### Automatic contract
- blockchain  

##### Dispute resolution 
- blockchain

##### Consortium of banks: sharing of immutable and verifiable information between untrusted parties (between multiple different organizations)
- blockchain

##### Bidding
- blockchain
  
##### Proof of ownership
- blockchain 

##### Insurance 
- blockchain

##### Patient records - to share between institutions
- distributed blockchain
  
##### Royalty payments
- distributed blockchain   

##### Flexible, Scalable, High-performance storage of data: 
-  NoSQL databases (Key-value, Document, Graph, FTSearch)

##### Session store - A session-oriented application such as a web application starts a session when a user logs in and is active until the user logs out or the session times out.
- key-value (DynamoDB, Cassandra) 

##### Shopping cart - During the holiday shopping season, an e-commerce website may receive billions of orders in seconds.
- key-value () 
  
##### Content management -  A document database is a great choice for content management applications such as blogs and video platforms. With a document database, each entity that the application tracks can be stored as a single document.
- document databases (MongoDB)

##### Catalogs - Document databases are efficient and effective for storing catalog information. For example, in an e-commerce application, different products usually have different numbers of attributes. Managing thousands of attributes in relational databases is inefficient, and the reading performance is affected. U
- document databases (Couchbase)

##### Real-time bidding - Real-time bidding refers to the buying and selling of online ad impressions.
- in-memory database

##### Caching - A cache is a high-speed data storage layer which stores a subset of data, typically transient in nature, so that future requests for that data are served up faster than is possible by accessing the data’s primary storage location.
- in-memory database

##### Gaming leaderboard - A relative gaming leaderboard shows a gamer's position relative to other players of a similar rank. 
- in-memory database

##### Recommendation engines - Graph databases are a good choice for recommendation applications. 
- graph database  

##### Fraud detection - connections between large data sets and identify patterns, a useful trait when it comes to spotting complex, modern fraud techniques.
- graph database   
  
##### Knowledge base
- graph database  

##### Search - Airbnb has recently rebuilt its internal data portal using Neo4j to allow employees to better find relevant dashboards and reports. German airline Lufthansa uses Neo4j for in-flight asset management, namely allowing staff to search the video film library and keep up with what has been rolled out where across the fleet
- graph database  

##### Identity and access management
- graph database  

##### Machine learning - Google has been running “graph-powered machine learning” for many of its AI-powered products, like inbox reminders and image recognition in Google Photos
- graph database  
  
#### Social Media and Social Network Graphs - Easily leverage social connections or infer relationships based on activity when you use a graph database to power your social network application. Community Cluster Analysis, Friend-of-Friend Recommendations, Influencer Analysis, Sharing & Collaboration, Social Recommendations
- graph database  
  
##### Network and IT operations -  “Model whole networks to figure out if one cell tower goes down how that scales across the network, or in the case of a breach how that moves across your architecture.”
- graph database  

##### Supply Chain - business supply chains are now more complex than ever, and they resemble a complex interconnected network. Brands can source produce from all over the globe from multiple suppliers, and the result is exactly the kind of interconnected system that graph databases excel at modeling.
- graph database 

##### Text search - Search-engine databases can handle full-text search faster than relational databases. For example, an e-commerce website can use search-engine databases to provide instant autocompletes or suggestions for its customers.
- search-engine database

##### Logging and analysis - Maintaining larger applications that are either distributed across several nodes or consist of several smaller applications searching for events in log files can become tedious. Search-engine databases can handle the logging more efficiently.
- search-engine database

##### Image or speech recognition
- Machine learning

### Technology index

##### NoSQL 
- graph database
  * Amazon Neptune
  * Neo4j
  * Ontotext graphdb
  
- document database (Flexibility) -  values are stored in a structured format that the database can understand. For example, a document could be a blog post and the comments and the tags stored in a denormalized way. The store can do more work (like indexing fields of the document) and you're not limited to query by key. 
  * MongoDB 
  * Couchbase 
  * Amazon DocumentDB
  
- key-value store (Simplicity) - Since key-value stores always use primary-key access, they generally have great performance and can be easily scaled.
  * DynamoDB
  * Cassandra
  
- in memory
  * redis
  * memcached
  
- search-engine  
  * Elasticsearch
  * Splunk

##### BlockChain Permissioned (confidential contracts, private transactions) distributed leger (blockchain): vote using private digital voting token which is linked to identification during registering to vote.
- Ethereum - Permissionless (open) Distributed leger 
- EOS - Permissionless (open) Distributed leger 
- AWS managed blockchain - Permissioned blockchain
- Hyperledger Fabric - Permissioned blockchain
- Infura
- Amazon QLDB
    Amazon QLDB is a fully managed ledger database that provides a transparent, immutable, and cryptographically verifiable transaction log ‎owned by a central trusted authority.
    Storage consumed by your Amazon QLDB ledger is billed per GB-month, and IOs consumed are billed per million requests. 
    Does not involve multi-party consensus

##### Messaging
- Kafka
- RabbitMq
- ActiveMQ

##### Secrets 
- HashiCorp Vault
- AWS Secret Store

##### Big Data 
- Spark
- Hadoop

##### Machine learning
- tensorflow
- aws machine learning
- google AI
