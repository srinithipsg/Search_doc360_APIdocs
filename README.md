# Search_doc360_APIdocs
### Document360 QA: Question Answering on document360 API documents

##### Project Description:

The objective of this project is to implement question answering task on a webpage documentation, where users input API endpoints, and the system retrieves the corresponding code samples from the respective endpoints.

Here's a step-by-step breakdown of the process:

**1) Web Scraping with Selenium**: Selenium, a powerful web automation tool, is used to scrape content from the documentation website. The following contents are extracted: API endpoints, HTTP request details, code samples, and page titles.

**2) Data Storage in CSV Format**:The scraped content is organized and stored in a structured CSV (Comma-Separated Values) file. 

**3) Data Loading with CSVLoader**:A CSVLoader is implemented to efficiently load the stored data from the CSV files. (Langchain framework)

**4) OpenAIEmbedding Model Integration**:This model is used to convert textual chunks into embeddings—a numerical representation of text. 

**5) Faiss Vector Store for Efficient Search**:To facilitate rapid and efficient similarity searches, we store the generated embeddings in a Faiss vector store. 

**6) RetrievalQA**: Querying relevant documents based on the query from the vector DB and Using an LLM,  will parse the answers from the relevant information 

By combining web scraping with advanced NLP techniques, this project offers an efficient and user-friendly solution for accessing and searching API documentation.
