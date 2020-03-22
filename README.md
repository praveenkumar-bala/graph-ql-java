# Graph QL Java

GraphQL is a query language for APIs and runtime for fulfilling those queries with the existing data. It was developed and open-sourced by Facebook in the year 2015.

## Why
  1) Provides a common interface between a client and the server for fetching the data and performing manipulations.
  2) Allows clients to define the required data structure and return the same from the server.
  3) Provides a complete and understandable description of data in API.
  4) It resolves the over fetching under fetching proplems
  
# Graph QL
The data represented using a graph of nodes and edges, nodes represent the java objects and edges represents the relationships between the objects
Graph QL is an alternative of REST & SOAP. It is not a replacement of REST & SOAP

# Graph QL VS REST

* Data Fetching - In REST Apis, multiple endpoints are used for gathering information. Where as in GraphQL a single endpoint is used because the data structure is not fixed in GraphQL

* Over Fetching / Under Fetching - In REST, fetching more or fewer data. But in GraphQL, only required information is fetched from the server
        
* Versoning - In REST, every updates we need to maintain current and old endpoints, but in GraphQL it is not required, since we can easily add new fields and types to Graph QL API without impact existing data.

# Graph QL Architecture

   1) Graph QL server with a connected database
   2) Graph QL server that integrates the existing system
   3) Hybrid Approach (Combination of above two)
   
# Core Concepts
## Schema Defination Language


# Maven Dependencies
  ```
  <dependency>
        <groupId>com.graphql-java</groupId>
        <artifactId>graphql-java</artifactId>
        <version>14.0</version>
  </dependency>
  ```
