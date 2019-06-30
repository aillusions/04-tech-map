
### Use cases

##### Voting 
- Permissioned blockchain

##### Cryptocurrency - direct transactions without central authority - money (cash is anonymous)
-  Permissionless blockchain

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
- key-value

##### Shopping cart - During the holiday shopping season, an e-commerce website may receive billions of orders in seconds.
- key-value
  
##### Content management -  A document database is a great choice for content management applications such as blogs and video platforms. With a document database, each entity that the application tracks can be stored as a single document.
- document databases

##### Catalogs - Document databases are efficient and effective for storing catalog information. For example, in an e-commerce application, different products usually have different numbers of attributes. Managing thousands of attributes in relational databases is inefficient, and the reading performance is affected. U
- document databases

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

##### Shortest route
- graph database 


### Technology index

##### NoSQL DB

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

##### BlockChain
- Ethereum - Permissionless (open) Distributed leger 
- EOS - Permissionless (open) Distributed leger 
- AWS managed blockchain - Permissioned blockchain
- Hyperledger Fabric - Permissioned blockchain
   * chain code (smart contract)  
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

##### Infrastructure
- Docker
- Packer
- Swarn
- saltstack
- kubernetes 
- Chef 
- Puppet 
- Ansible
- Terraform
- CloudFormation



Q: how would you
- store and retrieve comments for youtube videos
- implement chat 
- implement stream in a social network
- autonomously driving car
- site scrapper
- digital assistant
- find optimal route
- read text from scanned image
- canonical graph problems:  centrality, page-rank (most important/central node of graph), clustering
- store org hierarchy
- NLP - natural language processing (text adjacency graph)
- text translation
- video caption generation
- opinion/sentiment mining/extraction: text opinion extraction
- reviews engine
- retrieve and store real time analytics of a running process
- rate limit or billable rate
- implement ip blocking
- represent civil law in code and check if behaviour is legal or not
- government organisations responsibilities check if action falls into responsibility or not
- implement customer 360


Data Model (functional capabilities?)
    
    Key-value store: These databases are designed to store data in key-value pairs. These databases don?t have any schema and each data value contains an indexed key and a value for that key.
    - Cassandra
    - DynamoDb
    - BerkleyDb
    - Riak
    
    Column sore: These databases are used to store data in cells. These cells are grouped in columns of data, and these columns are further grouped into Column families.
    - BigTable
    - HBase
    - Hypertable
    
    Document store: These databases follow the basic idea of key-value stores where "documents" contain complex data and each document is assigned with a unique key, which is used to retrieve the document.
    - CouchDb
    - MongoDb
   
        
CAP (Non functional capabilities?)

- Consistency means that each client always has the same view of the data.
- Availability means that all clients can always read and write.
- Partition tolerance means that the system works well across physical network partitions.


Availability + Consistency
- RDBMS
        
Consistency + Partition Tolerance
- BigTable
- Hypertable
- HBase
- MongoDB
- Redis
- Memcached

Availability + Partition Tolerance
- Dynamo Db 
- Cassandra
- CouchDb

    
    
Replication models:
- eventual consistency
- strict consistency


CouchDB: CouchDB supports both master-master and master-slave replication.
MongoDB: MongoDB offers single-master replication with auto-election built-in.


technology stack examples:
- LAMP standing for Linux (operating system), Apache (web server), MySQL (database), PHP (programming language). LAMP is considered the most popular back-end stack and is appreciated for its scalability, security and high customization options. While most developers prefer Linux as the operating system, the same stack can be used with Windows or Mac OS without sacrificing the development quality.
- Python-Django based on the Python programming language. It also uses the Apache web server and MySQL database, as well as the Django framework, which is also written in Python. Developers love this stack for the possibility of quick development keeping the high level of quality. Many projects opt for Python-Django when creating their MVPs and other time-critical products.
- MEAN, which is an acronym of MongoDB (database), Express.js (application framework), AngularJS (front-end framework), Node.js (runtime environment). Here the stack structure is different, as it includes both the back-end and front-end development tools, and it is more correct to call it a full stack. MEAN is an implementation of the “JavaScript everywhere” concept using the same programming language both client-side and server-side. The back-end is based on Node.js, the first platform to use JavaScript in the back-end development. The MEAN stack is known for its high performance and flexibility, as well as a smooth learning curve, since it uses the same language across all components.
- MERN includes MongoDB, Express, React/Redux, and Node.js. Considering the popularity of ReactJS in front-end development and NodeJS in back-end development, this combination is reasonably called the most-used JavaScript stack for building high-end single-page applications. Except for the “one programming language across all tiers” benefit, MERN also offers a short learning curve, high productivity and enhanced agility. When comparing MEAN vs MERN, the choice boils down to React or Angular, and here it’s important to take into account the project’s requirements and goals, as well as the familiarity of JavaScript developer(s) with these front-end technologies.