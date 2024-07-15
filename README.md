# Todo

- [x] Create Folder structure
- [ ] Install packages
- [ ] Create Jupyter Notebook

## Project: Textbook Content Extraction, Indexing, and Retrieval

### Task 1: Textbook Selection and Content Extraction

- [ ] Select three textbooks with more than 300 pages each.

- [ ] Extract all relevant text content from the selected textbooks.

### Task 2: Hierarchical Tree-based Indexing

- [ ] Analyze textbook structures to identify hierarchical organization (chapters, sections, subsections).

- [ ] Create a hierarchical tree-based index for each textbook:
  - [ ] Root node represents the entire textbook.
  - [ ] Intermediate nodes represent chapters, sections, subsections.
  - [ ] Leaf nodes contain text content chunks.
- [ ] Assign unique identifiers to nodes and establish parent-child relationships.
- [ ] Store the hierarchical tree-based index in a suitable data structure or database.

### Task 3: Retrieval Techniques

- [ ] Implement query expansion techniques (synonym expansion, stemming, external knowledge bases).

- [ ] Combine BM25 and BERT/bi-encoder based retrieval methods (DPR, SPIDER).
- [ ] Experiment with different retrieval strategies and evaluate effectiveness.
- [ ] Re-rank retrieved data based on relevance and similarity to the query.

### Task 4: Multi-document/Topic/Section-based RAG

- [ ] Develop a Retrieval Augmented Generation (RAG) system:
  - [ ] Identify relevant documents using implemented retrieval techniques.
  - [ ] Traverse hierarchical tree-based indexes to retrieve pertinent sections.
  - [ ] Generate informative and coherent responses to user queries.

- [ ] Implement retrieval and ranking algorithms for selecting relevant content.

### Task 5: Question Answering

- [ ] Pass retrieved content from RAG system to an LLM for question answering.

- [ ] Generate accurate and relevant answers based on retrieved content.

### Task 6: User Interface (Optional)

- [ ] Create a user interface using Streamlit or Gradio.

- [ ] Allow users to input queries and display retrieved answers with relevant details.

- [ ] Write scripts (Backend)
- [ ] Create a fastAPI backend
- [ ] NextJS frontend
- [ ] Create Extensive README
- [ ] Dockerize
- [ ] Create Extensive README
