# dmc2021
This is the repository for Data Mining Cup 2021


Requirement:

The main task of this project is to recommend 5 closest items for each item in evaluation.csv file.

Data:

The data contain 3 separate files
1. Items: List of items and their features. Feature includes (itemID, title, author, publisher, main topic, subtopics)
2. Transaction: List of transactions and their processes. Data include (sessionID, itemID, click, basket, order)
3. Evaluation: List of items that need recommendation


Proposed solution:

1. Content-based filtering

Categrorical Similarity: (Goodall similarity OR General Similarity)
- Language: Based on Title, Author, Publisher
- Author:
- Publisher:

Numerical Similarity: (tree-like similarity, different types?????)
- Main Topic
- Subtopic

Normalize this

One proposed way to test:
- Check same item in transaction

2. Click-through pipepline rate:

- Simple NN or SVD???

- Divide