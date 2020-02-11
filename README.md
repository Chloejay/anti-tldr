I list tech related blogs, talks, slides and books I found interesting and useful, which so I use this repo as a cloud bookmark. 

The stuff I'm interested reading is programming, code architecture, engineering, machine (deep) learning, computer vision and clean code OOP/FP. 
<blockquote>
<ul>
    <li>
    The language is approx 80% is Python for sure. &#9749
    </li>
    <li>
    I will update when I found something interesting, so frequency range: [daily, weekly, monthly). 
    &#128521;
    </li>
</ul>
 </blockquote>

<h4>12-02-2020</h4>
<hr>
<ul>
<li>
<a href='https://blog.octo.com/en/cache-me-if-you-can-1/'>Cache me if you can – 1</a>
It talks about HTTP caching, offers an intro for why need caching (from CDN, reverse proxy part) and how it works by gaining theoretical insights about Cache-Control, Etag, If-Modified-Since and etc, analysis of the anatomy of a modern web application, to conclude caching is the solution to solce the latency bottleneck.
</li>
<li><a href='https://instagram-engineering.com/static-analysis-at-scale-an-instagram-story-8f498ab71a0c'>Static Analysis at Scale: An Instagram Story</a> 
A Python use case for introducing Linting for type checking, and implement with Pyre in production.
</li> 
<li>
<a href='https://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache'>Scalability for Dummies - Part 3: Cache</a>
It talks about in-memory cache Redis and two cache patterns, cached databse query and cached object. 
</li>
<li>
<a href=''>Julie Pagano: It's Dangerous to Go Alone: Battling the Invisible Monsters in Tech</a> A Pycon talk about issue and tool for imposter syndrome in programming community. 
</li>
</ul>

<h4>10-02-2020</h4>
<hr>
<ul>
    <li>
    <a href='https://itnext.io/introduction-to-event-streaming-with-kafka-and-kafdrop-73290625b1e2'>Introduction to Event Streaming with Kafka and Kafdrop
    </a>
    <!-- <br/> -->
    Introduce event-driven architecture by broken down to main components broker, zookeeper, producer and consumer for pubsub system. Illustrate relation among topic, message, partition, offset, covering load balancing and delivery gurantee model. By understand better, it introduce Kafka web UI tool KafDrop. 
    </li>
    <li>
    <a href='https://ordepdev.me/posts/tales-from-running-kafka-streams-in-production'>Tales from running Kafka Streams in Production
    </a>The key components in Kafka processing layer. 
    </li>
    <li>
    <a href=''>A Glossary of Functional Programming</a> A collection of simple (but reasonably precise) pedagogical definitions for a range of functional concepts.
    </li>
    <li>
    <a href='https://www.infoq.com/presentations/data-streaming-kafka-debezium/?utm_campaign=infoq_content&utm_source=twitter&utm_medium=feed&utm_term=architecture-design'>Practical Change Data Streaming Use Cases with Apache Kafka & Debezium 
    </a>Data is core in speaker Gunnar Morling (RedHat Open Source Data Engineer) talks about how to leverage CDC for reliable microservices integration, e.g. using the outbox pattern, as well as many other CDC applications (maintaining audit logs, driving streaming queries).
    </li>
    <li><a href='https://engineeringblog.yelp.com/2020/01/streams-and-monk-how-yelp-approaches-kafka-in-2020.html'>Streams and Monk – How Yelp is Approaching Kafka in 2020
    </a> Why and how Yelp redesigned their streaming infrastructure to scale clusters with a single configuration push, load balance and decommission brokers, automatically trigger rolling-restarts to pick up new cluster configuration, and more.
    </li> 
    <li><a href='https://www.jesseyates.com/2020/01/01/high-performance-kafka-producers.html'>High Performance Kafka Producers
    </a>Explain metrics for producer configurations including compression.type, batch.size, buffer.memory and etc to gain high performance for message flow through the Producer.</li>
    <li><a href='https://vladmihalcea.com/a-beginners-guide-to-cdc-change-data-capture/'>A beginner’s guide to CDC (Change Data Capture)
    </a>Simple introduction for CDC from classic database trigger which is event-condition-action logic to Debezium, a new open source project, stewarded by RedHat, mentioned how to use its connector to connect DBMS to extract CDC events, propagate them to Apache Kafka in OLTP use case. </li>
    <li><a href='https://netflixtechblog.com/dblog-a-generic-change-data-capture-framework-69351fb9099b'>DBLog: A Generic Change-Data-Capture Framework
    </a>DBLog is a Java-based framework, able to capture changes in real-time and to take dumps, it illustrate the log/dump processing, DBMS support and other core capabilities.</li>
    <li><a href='https://www.confluent.io/blog/kafka-streams-tables-part-4-elasticity-fault-tolerance-advanced-concepts/'>Streams and Tables in Apache Kafka: Elasticity, Fault Tolerance, and Other Advanced Concepts
    </a>Confluent Kafka blog, quality is high.</li>
</ul>