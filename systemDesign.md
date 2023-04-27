1. Load balancer --> between web servers and websites, allow every web sever have same amount data to process at the same time.

Advantage: very easy to expand. --> high scalaility
when sever is unfuntional, service can keep going --> high availability

load balancing algorithm eg. round robin, least connection, hashing

2. Database Design

Data model --> highly structured Data (Youtube, metadata)  
Database type --> Relational Database (MySQL, PostgreSQL)

Data model --> messy Data (e-commerce)  
Database type --> NoSQL Database (Cassandra, HBase, MongoDB)

all type needs Data partitioning, partitioning key
Relational Database doesn't mean it can't handle large scale.

3. Caching

load balancer protect web server, and caching protect database.
