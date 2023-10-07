
# WEEK 3 QUIZ

### Which of the following are general requirements for a programming language in order to support big data models?

A. Optimization of Specific Data Types
B. Utilize Map Reduction Methods
C. Enable Adding of More Racks
D. Handle Fault Tolerance
E. Support Big Data Operations
## ACDE


### What does IaaS provide?

A. Hardware Only
B. Computing Environment
C. Software On-Demand
## A


### What does PaaS provide?

A. Hardware Only
B. Software On-Demand
C. Computing Environment
## C


### What does SaaS provide?

A. Computing Environment
B. Software On-Demand
C. Hardware Only
## B


###  What are the two key components of HDFS and what are they used for?

A. FASTA for genome sequence and Rasters for geospatial data.
B. NameNode for metadata and DataNode for block storage.
C. NameNode for block storage and Data Node for metadata.
## B


### What is the job of the NameNode?

A. Coordinate operations and assigns tasks to Data Nodes
B. Listens from DataNode for block creation, deletion, and replication.
C. For gene sequencing calculations.
## A


### What is the order of the three steps to Map Reduce?

A. Shuffle and Sort -> Map -> Reduce
B. Map -> Reduce -> Shuffle and Sort
C. Shuffle and Sort -> Reduce -> Map
D. Map -> Shuffle and Sort -> Reduce
## D


### What is a benefit of using pre-built Hadoop images?

A. Guaranteed hardware support.
B. Less software choices to choose from.
C. Quick prototyping, deploying, and validating of projects.
D. Quick prototyping, deploying, and guaranteed bug free.
## C


### What is an example of open-source tools built for Hadoop and what does it do?

A. Zookeeper, analyze social graphs.
B. Zookeeper, management system for animal named related components.
C. Giraph, for processing large-scale graphs.
D. Giraph, for SQL-like queries.
E. Pig, for real-time and in-memory processing of big data.
## BC


### What is the difference between low level interfaces and high level interfaces?

A. Low level deals with interactivity while high level deals with storage and scheduling.
B. Low level deals with storage and scheduling while high level deals with interactivity.
## B


### Which of the following are problems to look out for when integrating your project with Hadoop?

A. Advanced Alogrithms
B. Random Data Access
C. Task Level Parallelism
D. Data Level Parallelism
E. Infrastructure Replacement
## ABCE


### As covered in the slides, which of the following are the major goals of Hadoop?

A. Facilitate a Shared Environment
B. Enable Scalability
C. Provide Value for Data
D. Latency Sensitive Tasks
E. Optimized for a Variety of Data Types
F. Handle Fault Tolerance
## ABCEF


### What is the purpose of YARN?

A. Allows various applications to run on the same Hadoop cluster.
B. Enables large scale data across clusters.
C. Implementation of Map Reduce.
## A


### What are the two main components for a data computation framework that were described in the slides?

A. Node Manager and Applications Master
B. Applications Master and Container
C. Resource Manager and Node Manager
D. Resource Manager and Container
E. Node Manager and Container
## C


#

# WEEK 3 [Intro to Hadoop]

### Download the text to Alice's Adventures in Wonderland from http://www.gutenberg.org/files/11/11-0.txt (If it redirects you to a page with a welcome popup, click on the "Plain Text UTF-8" option on that page or just download the attachment below) and run wordcount on it. This can be done by using hadoop commands. How many times does the word Cheshire occur? (Do not include the word 'Cheshire with an apostrophe. The string -->'Cheshire<-- does not count)

## Enter a number: 6


### The set of example MapReduce applications includes wordmedian, which computes the median length of words in a text file. If you run wordmedian using words.txt (the Shakespeare text) as input, what is the median word length? Note that wordmedian prints the median length to the terminal at the end of the MapReduce job; the output file does not contain the median length.

## Enter a number: 4


### (Questions 1-3 pertain to the video lecture "Exploring the Relational Data Model of CSV") What is the approximate population of La Paz county in the state of Arizona for the CENSUS2010POP (column H)? (Choose the best answer.)
A. 20000
B. 10000
C. 25000
D. 15000
## A


### What county in the state of Wyoming has the smallest estimated population?

A. Uinta
B. Niobrara
C. Platte
D. Sweetwater
## B


### At 2:45 of the video, the Instructor creates a filter for all of the counties in California with a population greater than 1,000,000. However, included in the results is the entire state of California. This anomalous value might skew our analysis if, for example, we wanted to compute the average population of these results. What additional filter might work to resolve this problem?

A. Add a filter to detect and remove results which do not include the word "County" in column G.
B. Add a filter which finds all counties with population greater than 100,000 AND less than 10,000,000 for column H (CENSUS2010POP).
C. Add a filter where the value in column E is greater than 1,000,000.
D. None of the above
## A


### (Questions 4 and 5 pertain to the video "Exploring Sensor Data") How often (in seconds) do the R5 measurements occur?
A. 60
B. 50
C. 40
D. 30
## A


### What is the field for rain accumulation?
A. Sm
B. Dn
C. Dx
D. Rc
## D


### (Questions 6 and 7 pertain to the video lecture "Exploring the Array Data Model of an Image") What is the (Red, Green, Blue) pixel value for location 500, 2000?

A. (134, 145, 46)
B. (50, 156, 182)
C. (100, 123, 149)
D. (163, 118, 79)
## D


### Is this value likely to be land or ocean?

A. Ocean
B. Land
## B


### (Questions 8 and 9 pertain to the video lecture "Exploring the Semistructured Data Model of JSON") Given a tweet, what path would you most likely enter to obtain a count of the number of followers for a user?

A. user/followers_count
B. user/statuses_count
C. user/listed_count
D. None of the above
## A


### Which of the following fields are nested within the 'entities' field (select all that apply)?

A. user_mentions
B. urls
C. symbols
D. views
E. events
F. tweets
## ABC


### What is a possible pitfall of utilizing Excel as a way to manipulate small databases?

A. Excel does not enforce many principles of relational data models.
B. Excel does not allow algorithms for data manipulation.
C. Excel is a user program and thus cannot run on a server.
## A


### What does the term "atomic" mean in the context of relational databases?

A. A tuple that cannot be reduced.
B. One unit of information that cannot be decomposed.
C. A column or row of data. Depends on the context.
D. Fixed schema of a particular database.
## B


### What is the Pareto-Optimality problem?

A. Find the shortest path from source node to target node.
B. Find the best possible path given two or more optimization criteria where neither constraint can be fully optimized simultaneously.
C. Find the optimal path that requires going through specific nodes given by the user.
## B


### What constitutes a community within a graph?

A. Many anomalous neighborhoods within the same vicinity.
B. A dense amount of edge connections between nodes in a community and a few connections across communities.
C. A neighborhood defined by an integer constant K around a specific node. All K+1 nodes belong in another community.
D. High density of nodes at a certain location.
## B


### Why are trees useful for semi-structured data such as XML and JSON?

A. Trees take advantage of the parent-child relationship of the data for easy navigation.
B. Computers can easily visualize the data with a tree structure.
C. It is not always the case that XML and JSON can be represented as trees.
D. They are only useful for XML data as tree-like structure is apparent with tags. While JSON does not contain a tree-like structure as it contains arrays.
## A


### What is the general purpose of modeling data as vectors?

A. Results can be ordered by similarity using vector projection.
B. Enables image searching.
C. Enables weighting of the query.
D. The ability to normalize vectors allowing probability distributions.
## A


### For the following questions 7, 8, and 9, suppose a registration website creates data with the following fields for each person registered (note: if the user does not input a value, NULL is stored instead): Name, Date, Address, and Account Number. Suppose we collect data month by month. Each month, we would have a batch of data containing the fields listed above. At the end of the year, we want to summarize our registrant activities for the entire year, so we would remove redundancies in our data by removing any records with duplicate account numbers from month to month. What type of operation do we use in this scenario?

A. Union
B. Join
C. Subsetting
D. Not an Operation
## A


### From the information given in question 7, what are the constraints, if any, which we have placed on the Account Number field for the end of year collection?

A. Account should have at most n digits.
B. There are no constraints.
C. If we had n duplicate Account Numbers then we will remove n-1 duplicate fields.
D. Account Number should be unique.
## D


### Suppose 100 people signup for our system and of the 100 people, 60 of them did not input an address. The system lists the values as NULL for these empty entries in the address field. Would this situation still have structure for our data?

A. Yes the data has structure because we have placed a structural constraint on the data, thus the data will always have the originally defined structure.
B. No because the majority of data do not have a specific field filled, thus our originally defined structure is lost.
## A


### What is true between data modeling and the formatting of the data?

A. The data does not necessarily need to be formatted in a way that represents the data model. Just so long as it can be extrapolated.
B. There is always one specific schema for storing model data that is the best and preferred method for the specific data representation.
C. There is a one to one correspondence between formatting data and data modeling. For every model of data, there is only one way to store the data.
## A


### What is streaming?

A. Using static data stored from a real time source in order to process and guide the application.
B. Calculating results using real time data otherwise known as streaming data.
C. Utilizing real time data to compute and change the state of an application continuously.
D. Using sensors to manipulate the system, such as a smart car being able to drive by itself using sensors to detect road hazards.
## C


### Of the following, what best describes the properties of working with streaming data?

A. Independent computations that do not rely on previous or future data.
B. Does not ping the source interactively for a response upon receiving the data.
C. Always unbounded in sequence, in other words, data is not guaranteed to be in order.
D. Data is always utilized for streaming the application.
E. Small time windows for working with data.
F. Data manipulation is near real time.
## ABEF


### What is a characteristic of streaming data?

A. The data is finite and requires only finite time and space to process the data.
B. The data is unbounded in size and the size determines the time and space of processing the data.
C. Data is finite in size and size determines the time and space of processing the data.
D. Data is unbounded in size but requires only finite time and space to process it.
## D


### What type of algorithm is required for analyzing streaming data?

A. Accurate and Consistent
B. Fast and Simple
C. Fast and Complex
D. Accurate and Memory Efficient
## B


### What is lambda architecture?

A. A specific method for processing streaming data using special real time processes.
B. A method to process streaming data by utilizing batch processing and real time processing.
C. A specific hardware architecture for a server made specifically for processing real time data.
## B


### Of the following, which best represents the challenge regarding the size and frequency of data?

A. There may not be data to produce the notion of size and frequency.
B. The size and frequency of the streaming data may be too small.
C. The size and frequency of the streaming data may be sporadic.
## C


### What is the difference between data lakes and data warehouses?

A. Data lakes house raw data while data warehouses contain pre-formatted data.
B. Data lakes utilize hierarchical systems while data warehouses use object storage.
C. Data lakes contain only files while data warehouses contain only databases.
## A


### What is schema-on-read?

A. The process where formatted data is given structure when read.
B. Another name for data lakes.
C. Data is stored as raw data until it is read by an application where the application assigns structure.
D. The process where data is pre-formatted prior to being read but the schema is loaded on read.
## C


### The desired characteristics of a BDMS include (select all that apply):

A. A flexible semi-structured data model
B. Support for ACID
C. A full query language
D. Continuous data ingestion
E. Support for common "Big Data" data types
F. Narrow range of query sizes
## ACDE


### Fill in the blank with the best answer: CAP theorem states that _________ all at once within a distributed computer system?

A. it is necessary to have consistency, availability, and partition tolerance
B. it is necessary to have consistency, accuracy, and partial tolerance
C. it is impossible to have consistency, accuracy, and partial tolerance
D. it is impossible to have consistency, availability, and partition tolerance
## D


### What is the purpose of the acronym BASE?

A. To impose properties on a BDMS in order to guarantee certain results.
B. Enables stricter enforcement of ACID type design.
C. The same as ACID.
D. To overcome CAP theorem.
## A


### What are ziplists in Redis?

A. A special type of data type that can store hashes that point to multiple attributes.
B. A special type of data type that can store up to 512 mb of image data.
C. A compressed list that is stored within the value of the database.
D. A look up table that is stored as a value in the database. Look up table points to actual values in memory.
## C


### What is one of the main features of Aerospike?

A. Enables real time data streaming from external sources.
B. Support for geospatial data storage and geospatial queries.
C. Better equipped for string based search applications.
D. Images as values within the database.
## B


### What database would be best suited for the following scenario: An app development company is trying to implement a cloud based storage system for their new map-based app. The cloud will manage the longitude and latitude of the data in order to track user location.

A. Solr
B. Redis
C. Aerospike
D. Vertica
## C


### What database would be best suited for the following scenario: A big wholesale company is trying to implement a search engine for their products.

A. Redis
B. Aerospike
C. Solr
D. Vertica
## C


### Which of the following data types are supported by Redis? (select all that apply)

A. Strings
B. Lists
C. Images
D. Hashes
E. Sorted Sets
F. Streaming Video
## ABDE


### What does it mean for a query language to be declarative?

A. The language specifies both the process of how to obtain the data and specifies what data to obtain.
B. The language specifies what data to obtain.
C. The language specifies the process of how to obtain the data.
D. A language specific declaration of data types in order to define the method of data retrieval.
## B


### Use the following table named "user_table" to answer the next 2 problems.

userId | username | email
1 | admin | admin@corporate.moe
2 | h4xor | 1337@rawr.cte

How would you go about querying the entire username column (however many)?

A. SELECT username FROM user_table
B. SELECT user_table FROM username
C. SELECT username FROM user_table WHERE userId=1
D. SELECT username FROM userId WHERE *
## A


### How would you go about querying the entire database table (please refer to question 2's table)?

A. SELECT username, email FROM userId
B. SELECT * FROM user_table
C. SELECT user_table FROM *
D. SELECT FROM WHERE user_table
## B


### What is the global indexing table?

A. A global table that uses a specific technique called indexing and the table uses an index as the primary key.
B. An index table in order to keep track of data records within one machine.
C. An index table in order to keep track of a given data type that might exist within multiple machines.
D. An index table in order to keep track of a given data type that might exist within one machine.
## C


### What are the three computing steps of a semi-join?

A. Project, Ship, Reduce
B. Project, Decompose, Send
C. Index, Join, Display
D. Query, Join, Display
E. None Applicable
## A


### What is the purpose of a semi-join?

A. Increase the efficiency of sending data across multiple machines.
B. Another name for join: an operation to combine two tables by column.
C. Increase the speed of the join for trade-off of increased data transmission cost.
## A


### What is a subquery?

A. A query statement within another query.
B. A short query than normal.
C. An alternative query that acts as a substitute for another query.
## A


### What is a correlated subquery?

A. A type of query that contains a relationship between a variable attribute x and a variable attribute y. The two variables have a dependent relationship causing a correlation.
B. A type of query that contains a subquery that requires information from a query one level up.
C. A type of query that requires two tables in order to calculate values.
## B


### What is the purpose of GROUP BY queries?

A. Enables calculations based on specific columns of the table.
B. Required before you can use functions like AVG, SUM, MIN, MAX, COUNT.
C. Enables queries within queries.
## A


