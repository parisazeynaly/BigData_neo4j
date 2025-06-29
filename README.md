# BigData_neo4j
# NLP-Powered Social Graph with Neo4j

This project combines **Natural Language Processing (NLP)** with **graph databases** to analyze Twitter data as a social graph.

We use the [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140), which contains 1.6 million tweets, each labeled as positive, negative, or neutral. The goal is to:

- Clean and preprocess tweet text
- Extract user mentions and relationships
- Use sentiment to enrich the relationships
- Build and visualize a **social network graph** using **Neo4j**
- Query and analyze the graph using **Cypher**

---

## 🚀 Key Features

- NLP preprocessing for Twitter text
- Sentiment classification included in the graph
- Graph model: `User → MENTIONED → User`
- Visualized in Neo4j with powerful Cypher queries
- Designed for mid-sized data (1M+ rows)

---

## 🛠 Technologies Used

- Python (pandas, re, tqdm)
- Neo4j (with `neo4j` Python driver)
- Cypher Query Language
- [Sentiment140 dataset](https://www.kaggle.com/datasets/kazanova/sentiment140)
