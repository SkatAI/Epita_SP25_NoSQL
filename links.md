# Links

## MongoDB

- aggregation pipelines

[fr] https://studio3t.com/fr/knowledge-base/articles/mongodb-aggregation-framework/

- mongosh

https://medium.com/@amitvsolutions/mongodb-mongosh-in-action-d815915b480f

- install mongodb on windows

https://medium.com/@LondonAppBrewery/how-to-download-install-mongodb-on-windows-4ee4b3493514

- schema design

https://medium.com/@farihatulmaria/how-to-design-efficient-schemas-in-mongodb-for-highly-scalable-applications-69e616725d32

https://learn.mongodb.com/courses/schema-design-patterns

- indexing in mongodb
-
https://medium.com/@farihatulmaria/what-are-the-best-practices-for-indexing-in-mongodb-to-optimize-query-performance-c2bea64453fb

https://medium.com/@farihatulmaria/avoiding-common-pitfalls-in-mongodb-indexing-an-advanced-guide-e27a4c1a77c7


- internal architecture

https://medium.com/@hnasr/mongodb-internal-architecture-9a32f1403d6f

https://vishalrana9915.medium.com/deep-dive-into-mongodb-and-its-architecture-d6290b6d2285

- update performance

https://medium.com/shelf-io-engineering/how-to-update-63-million-records-in-mongodb-50-faster-a6dbf23ec9b3

- vector search in mongodb

https://www.mongodb.com/docs/atlas/atlas-vector-search/tutorials/vector-search-quick-start/?tck=ai_as_web

https://www.mongodb.com/docs/atlas/atlas-vector-search/tutorials/vector-search-tutorial/

- use case vector search audio and embeddings

https://ai.gopubby.com/empowering-wind-turbine-diagnostics-with-vector-search-ais-transformative-role-in-manufacturing-ee6cb9c74878

- build knowledge graph

https://medium.com/neo4j/llm-knowledge-graph-builder-first-release-of-2025-532828c4ba76

https://open.substack.com/pub/ontologist/p/creating-a-simple-knowledge-graph?r=f2r6v&utm_medium=ios

- neo4j bollywood graph

https://medium.com/towards-data-science/neo4j-for-bollywood-5ceb371031f1

- cypher + gpt4

https://medium.com/neo4j/generating-cypher-queries-with-chatgpt-4-on-any-graph-schema-a57d7082a7e7

- neo4j shortest path algos

https://medium.com/data-science-in-your-pocket/graph-analytics-pathfinding-algorithms-using-neo4j-c9bda1915077

https://medium.com/data-science-in-your-pocket/graph-analytics-relationship-link-prediction-in-graphs-using-neo4j-79a81716e73a

- neo4j based app  graph academy

https://medium.com/neo4j/building-an-educational-platform-on-neo4j-d7dc195b9466

- embeddings

https://levelup.gitconnected.com/vector-embeddings-explained-for-developers-6bd9800d3635



# DuckDb

https://www.dbreunig.com/2025/05/03/duckdb-is-the-most-impactful-geospatial-software-in-a-decade.html


In contrast to transactional queries (lots of small reads/writes like in banking apps), analytical queries focus on big reads, few writes, and complex calculations — like building reports, dashboards, or running data science workflows.

DuckDB is optimized for this by:

    Using a columnar storage format (read only the needed columns)

    Running operations in batches and in memory

    Applying vectorized execution (processes many rows at once)

In short: fast for reading and analyzing big datasets, not designed for frequent small updates.



