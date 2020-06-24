# System Analysis & Design

 1. Types of System Design
    1. Logical Design
    2. Physical Design
 2. Design Strategies
    1. Top-Down Strategy
    2. Bottom-Up Strategy
    3. Structured Design
 3. System Design Principles
    1. Separation of Concerns
      1. Reusability
      2. Maintainability
      3. Extensibility
    2. Highly Cohesive and Loosely Coupled
    3. Event Driven Architecture
    4. Reduce the amount of processing in the Client request path
    5. Use Effective Caches to make it highly responsive
    6. Distributed System Characteristics
       1. Scalability
          1. Vertical Scaling
          2. Horizontal Scaling
       2. Reliability
       3. Availability
       4. Simplicity
    7. Use Asynchronous process

#### Trade-offs in a large scale system like Twitter
  1. Performance Vs Scalability
  2. Latency Vs Throughput
  3. Availability Vs Consistency(CAP Theorem)

#### Components of a large scale system
1. Databases/Storage Layer
   1. SQL vs NoSQL (Example :  RDS and DynamoDb)
   2. Sharding or Data Partitioning
   3. Indexes (Lab Session)
   4. Consistent Hashing
   5. ElasticSearch
2. Cache
   1. Caching Policies: Write - Through/Around/Back
   2. Elasticache
3. Queue
   1. Kinesis
   2. SQS
4. DNS
5. CDN
6. Load Balancer
7. System Profiling
    1. How to identify bottlenecks?
    2. Calculations
    3. Splunk, New Relic / DataDog

#### System Design Problems
1. Designing a URL Shortening service like TinyURL
2. Designing Pastebin
3. Designing Instagram
4. Designing Dropbox
5. Designing Facebook Messenger
6. Designing Twitter
7. Designing Youtube or Netflix
8. Designing Typeahead Suggestion
9. Designing an API Rate Limiter
10. Designing Twitter Search
11. Designing a Web Crawler
12. Designing Facebook’s Newsfeed
13. Designing Yelp or Nearby Friends
14. Designing Uber backend
15. Design Ticketmaster (*New*)


#### Glocery
* System Design Basics
* Key Characteristics of Distributed Systems
* Load Balancing
* Caching
* Data Partitioning
* Indexes
* Proxies
* Redundancy and Replication
* SQL vs. NoSQL
* CAP Theorem
* Consistent Hashing
* Long-Polling vs WebSockets vs Server-Sent Events

#### Refernce
  * [SystemsExpert](https://www.algoexpert.io/systems/product)
  * [Systems Design Fundamentals](https://www.algoexpert.io/systems/fundamentals)
  * [8 Systems Design Interview Questions](https://www.algoexpert.io/systems/questions)
    - Design AlgoExpert
    - Design A Code Deployment System
    - Design A Stockbroker
    - Design Facebook News Feed
    - Design Google Drive
    - Design The Reddit API
    - Design Netflix
    - Design The Uber API
  * [System Analysis and Design Tutorial - tutorialspoint](https://www.tutorialspoint.com/system_analysis_and_design/index.htm)
  * [Software System Design Principles](https://www.javacodegeeks.com/2019/05/software-system-design-principles.html)
  * [educative.io - Grokking the System Design Interview](https://www.educative.io/courses/grokking-the-system-design-interview?affiliate_id=5082902844932096&utm_source=google&utm_medium=cpc&utm_campaign=grokking-manual&gclid=CjwKCAjw88v3BRBFEiwApwLevea89P3kbELzgxq76uPAzVGy1StCgHvPbuQ7YRNfvB6xufmvPNdnaRoCRzEQAvD_BwE)
  * [System Design - Gaurav Sen](https://www.youtube.com/playlist?list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX)
  * [System Design Course](https://get.interviewready.io/courses/system-design-interview-prep)
  * [InterviewBit Academy - System Design Course](https://www.interviewbit.com/courses/system-design/)
  * https://www.coursehero.com/file/p5t4igg/System-design-is-divided-into-two-types-Logical-Design-The-logical-design-of-a/
