## Run Graph Database in Docker
- run the neo4j docker
```sh
docker run --publish=7474:7474 --publish=7687:7687 --volume=$HOME/neo4j/data:/data --env=NEO4J_AUTH=none  neo4j
```
- run the dgraph docker
```sh
docker run --rm -it  -p 8080:8080 -p 9080:9080 -p 8000:8000 -v ~/dgraph:/dgraph dgraph/standalone:v20.11.2
```


## Concepts
RDF Triplestore
<p align="center"><img style="display: block; width: 600px; margin: 0 auto;" src=img/2021-03-01-10-28-21.png alt="no image found"></p>


## Modeling
- [Arrows](https://arrows.app/)

## References
- [GraphQL for dgraph](https://en.wikipedia.org/wiki/GraphQL)
- [Cypher Query Language for Neo4j](https://en.wikipedia.org/wiki/Cypher_(query_language))
- [SPARQL for AWS Neptune](https://en.wikipedia.org/wiki/SPARQL)
- [Gremlin for AWS Neptune](https://en.wikipedia.org/wiki/Gremlin_(query_language))
- [AWS/Graph-Notebook](https://github.com/aws/graph-notebook/#prerequisites)