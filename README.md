## Generating Knowledge Graphs from Text Data
This repository explores the idea of generating Knowledge Graphs by leveraging the concepts of NLP &amp; Graph Theory. 

### What is a Knowledge Graph?
A knowledge graph (KG) represents a collection of interlinked descriptions of entities – real-world objects and events, or abstract concepts (e.g., documents) – where:

1. Descriptions have formal semantics that allow both people and computers to process them in an efficient and unambiguous manner
2. Entity descriptions contribute to one another, forming a network, where each entity represents part of the description of the entities, related to it, and provides context for their interpretation. <br /> <br />

**_Simplified view of a Knowledge Graph:_** <br /> <br />
![alt_text](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/10/graph_link.png)

**_Example of a Knowledge Graph:_** <br /> <br />
![alt_text](https://cdn.analyticsvidhya.com/wp-content/uploads/2019/10/APEC.png)

### Steps used to generate a Knowledge Graph:
1. Data collection (from Wikipedia)
2. Text cleaning & Coreference resolution
3. Entity pairs extraction
4. Simplifying the relations
5. Plotting the knowledge graph
6. Ranking sentences per relation

### Conclusion
Knowledge Graphs can help provide meaningful and consise insights into our data. A number of specific uses and applications rely on knowledge graphs. Examples include data and information-heavy services such as intelligent content and package reuse, responsive and contextually aware content recommendation, knowledge graph powered drug discovery, semantic search, investment market intelligence, information discovery in regulatory documents, advanced drug safety analytics, etc.

### References
[[1] What is a Knowledge Graph?](https://www.ontotext.com/knowledgehub/fundamentals/what-is-a-knowledge-graph/) <br />
[[2] Knowledge Graphs](https://www.analyticsvidhya.com/blog/2019/10/how-to-build-knowledge-graph-text-using-spacy/) <br />
[[3] Coreference Resolution](https://nlp.stanford.edu/projects/coref.shtml) <br />
[[4] Wikipedia API](https://towardsdatascience.com/wikipedia-api-for-python-241cfae09f1c) <br />
[[5] NetworkX](https://networkx.org/documentation/stable/tutorial.html) <br />
