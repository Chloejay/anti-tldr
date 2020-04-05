I document tech related List(blog, talk, slide and book)s I found interesting and useful, which so I use this repo as a cloud bookmark. 

Functional programming and programming in general, code architecture, engineering, machine (deep) learning, computer vision. 
<blockquote>
<ul>
    <li>
    About Scala and Python. &#9749
    </li>
    <li>
    I will update when I found something interesting. 
    &#128521;
    </li>
</ul>
</blockquote>

<h4>04-04-2020</h4>
<hr>
<ul>
<li>
<a href='https://bartoszmilewski.com/2014/11/24/types-and-functions/'>Types and Functions</a> Types are about composability, type system to design a type family (type parameters) to improve program performance.  
</li>
</ul>

<h4>31-03-2020</h4>
<hr>
<ul>
<li>
<a href='https://blog.kubukoz.com/what-makes-a-function-pure'>What makes a function pure?</a>Pure function has feature totality, determinism, purity. 
</li>
<li>
<a href="http://degoes.net/articles/easy-monads">A Beginner-Friendly Tour through Functional Programming in Scala</a> Pure FP! 
</li>
<li>
<a href="http://blog.kamkor.me/Covariance-And-Contravariance-In-Scala/">Covariance and contravariance in Scala</a> Concept of covariance and contravariance in Scala, type parameter for subtyping.
</li>
<li>
<a href="https://medium.com/javarevisited/variance-in-java-and-scala-63af925d21dc">A Complete Guide to Variance in Java and Scala</a> 
</li>
<li>
<a href="http://james-iry.blogspot.com/2007/09/monads-are-elephants-part-1.html">Monads are Elephants Part 1</a> It talks about using unit and flatMap for Monad concept. 
</li>
<li>
<a href="https://www.geekabyte.io/2018/05/thoughts-on-dealing-with-having-another.html">Thoughts On Working With Nested Monad Within The Future Monad In Scala</a> Use sugared `for comprehension`, encode the failure in Future or Monad Transformers with Cats EitherT for monad Future[Either[F, S]]. 
</li>
<li>
<a href="http://www.lihaoyi.com/post/StrategicScalaStylePrincipleofLeastPower.html">Strategic Scala Style: Principle of Least Power</a> 
</li> This is a style guidance to write clean and DRY Scala code, by using Principle of Least Power philosophy, refactoring code, don't over engineer and avoid complexity. 
<li>
<a href='http://www.lihaoyi.com/post/WhatsFunctionalProgrammingAllAbout.html'>What's Functional Programming All About?</a>"FP" in software world. 
</li> 
</ul>

<h4>22-03-2020</h4>
<hr>
<ul>
<li>
<a href="https://squeakyvessel.com/2015/05/12/mature-developers/">Mature Developers</a> This article talks about the quality that mature developer should build.
</li>
<li>
<a href="https://stevedower.id.au/blog/most-critical-python-metric">The most critical Python code metric</a> It suggests that for dynamic code, writing tests is actually the best way to ensure your architecture is well designed. 
</li>
<li>
<a href="https://www.iteratorshq.com/blog/tagless-with-discipline-testing-scala-code-the-right-way/">Tagless with Discipline — Testing Scala Code the Right Way</a>
The code discipline about how to write test and use library Discipline to write Scala test. 
</li>
<li>
<a href="http://squidarth.com/scala/types/2019/01/11/type-erasure-scala.html">Type Erasure in Scala</a> Scala is type-safe language, the code if can compiled but can't be available to be used in run-time, for type erasure error. Using Scala reflection API to inspect the types of the instance at run-time is a solution, or use polymorphism subtypes. 
</li>
<li>
<a href="https://medium.com/@olxc/the-evolution-of-a-scala-programmer-1b7a709fb71f">The Evolution of a Scala Programmer</a> Good examples of Scala patterns.
</li>
<li>
<a href="https://medium.com/@antoine.doeraene/a-little-bit-of-data-science-in-scala-5caba1ad8d9f">A little bit of Data Science in Scala</a> It talks how to use Scala for DS project, especially Scala collection library is easy and fast for data processing and similar to Spark API.
</li>
</ul>

<h4>16-03-2020</h4>
<hr>
<ul>
<li>
<a href="http://blogs.tedneward.com/patterns/abstractfactory/">Abstract Factory</a> Factory pattern for Scala. 
</li>
<li><a href="https://pavelfatin.com/design-patterns-in-scala/">Design Patterns in Scala</a> 
</li>
<li><a href='https://medium.com/@tonistiigi/advanced-multi-stage-build-patterns-6f741b852fae'>Advanced multi-stage build patterns</a> It introduces patterns how to write multiple FROM/--from flag in Dockerfile by constructing multiple stages. 
</li>
</ul>

<h4>06-03-2020</h4>
<hr>
<ul>
<li>
<a href='https://geirsson.com/scalameta.html'>Three cool things you can do with Scalameta</a> The usage about Scalameta library. 
</li>
</ul>

<h4>24-02-2020</h4>
<hr>
<ul>
<li><a href='http://michal.karzynski.pl/blog/2019/05/26/python-project-maturity-checklist/'>Python project maturity checklist</a> This article is written by Michał Karzyński, who gives a typical checklist how to turn Python script into a fully fledged open-source project. It covers step-to-step guide how to use setuptools, Black, pre-commit etc. 
</li>
<li><a href='https://ep2019.europython.eu/talks/ZJ7mNEK-the-soul-of-the-beast/'>The soul of the beast, Everything about Python's grammar</a> Hacking the grammar, the talk can be found on this <a href='https://www.youtube.com/watch?v=avLK67SHeAs'>link</a>.
</li>
<li><a href='https://glyph.twistedmatrix.com/2020/02/modules-for-maintenance.html'>Modularity for Maintenance</a>
Never send a human to do a machine’s job.
</li>
<li><a href='https://blog.colinbreck.com/on-eliminating-error-in-distributed-software-systems/'>On Eliminating Error in Distributed Software Systems</a> It reviews some common techniques used to eliminate errors in software systems: testing, the type system, functional programming, and formal verification.
</li> 
<li><a href='https://pythonspeed.com/docker/'>Production-ready Docker packaging</a>
Docker packaging guide for Python.</li>
</ul>

<h4>20-02-2020</h4>
<hr>
<ul>
<li><a href='https://overreacted.io/my-decade-in-review/'>My Decade in Review</a>
This article is whole story about Dan Abramov, a self taught but one of the best programmers in web dev world. Bookmark it by inspired by his open source spirit.
</li>
<li><a href='https://storiesinmypocket.com/articles/refactoring-and-asking-forgiveness/'>Refactoring and asking for forgiveness</a> This article talks about how to use programming pattern EAEP (easier to ask for forgiveness than permission), instead of LBYL (look before you leap).</li> 
<li>
<a href=''>From Academia to Data Science</a>
Fill the gap between academic CS and industrial ML/DL. 
</li> 
</ul>

<h4>15-02-2020</h4>
<hr>
<ul>
<li><a href='https://multithreaded.stitchfix.com/blog/2018/09/05/datahighway/'>Putting the Power of Kafka into the Hands of Data Scientists</a> Prototype and build data integration Highway that design self-service layer on top of Kafka, use Kafka Connect for integration.</li>
<li><a href='https://sourcery.ai/blog/python-best-practices/'>How to set up a perfect Python project</a> It introduces good practice how to set up and design a Python project using Pytest for test, Black for formatting, isort for import sorting, mypy for static typing, flake8 for linting, pre-commit for Git hook that runs scripts automatically when push/commit. 
</li> 
<li><a href=''>Yes silver bullet</a> This article is delightful. Reframe essential and accidental complex in software development, quoted William Gibson's word, <i><strong>"The future is already here — it's just not very evenly distributed." </strong></i> is appropriately explain changes such as Automated testing, Statically typed functional programming.</li>
</ul>

<h4>13-02-2020</h4>
<hr>
<ul>
<li><a href='https://tselai.com/modern-data-practice-and-the-sql-tradition.html'>
Modern Data Practice and the SQL Tradition 
</a>Reconsider to take advantage of advanced RDBMS features (such as triggers and stored procedures) and propose to "use RDBMS in the first place" by comparing performance with NoSQL, Python library Pandas and distributed system ElasticSearch. 
</li>
</ul>

<h4>12-02-2020</h4>
<hr>
<ul>
<li>
<a href='https://blog.octo.com/en/cache-me-if-you-can-1/'>Cache me if you can – 1</a>
It talks about HTTP caching, offers an intro for why need caching (from CDN, reverse proxy part) and how it works by gaining theoretical insights about Cache-Control, Etag, If-Modified-Since and etc, analysis of the anatomy of a modern web application, to conclude caching is solution to solve the latency bottleneck.
</li>
<li><a href='https://instagram-engineering.com/static-analysis-at-scale-an-instagram-story-8f498ab71a0c'>Static Analysis at Scale: An Instagram Story</a> 
A Python use case for introducing Linting for type checking, and implement with Pyre in production.
</li> 
<li>
<a href='https://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache'>Scalability for Dummies - Part 3: Cache</a>
It talks about in-memory cache Redis and two cache patterns, cached database query and cached object. 
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
    Introduce event-driven architecture by broken down to main components broker, zookeeper, producer and consumer for pubsub system. Illustrate relation among topic, message, partition, offset, covering load balancing and delivery guarantee model. By understand better, it introduces Kafka web UI tool KafDrop. 
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