BioBot
======

BioBot is a RAG (Retrieval-Augmented Generation) based chatbot designed to provide answers to medical and biological queries and questions. It utilizes the PubMedQA dataset available in Hugging Face for its knowledge base. The technology stack includes Chainlit, Nomic AI's embedding model, Gemini, Langchain, and ChromaDB.

Installation
------------

To run BioBot, follow these steps:
Install the requirements
```bash
pip install -r requirements.txt
```
    
1.  Run **create\_csv\_data.py** to generate a CSV file of training data.
    
2.  Execute **create\_text\_data.py** to transform the CSV inputs into a text file.
    
3.  Run **ingest.py** to store the data in the vector database.
    
4.  Finally, start the application by running **app.py**.
    

Usage
-----

Once the application is running, users can interact with BioBot to ask medical and biological questions. The chatbot leverages its knowledge base to provide informative responses.

Contribution
------------

Feel free to contribute to this project by suggesting improvements or enhancements. We are constantly working on making BioBot more responsive and accurate in answering queries.

Feedback
--------

If you have any queries or suggestions for improvement, don't hesitate to reach out. Your feedback is invaluable in making BioBot a more useful tool for exploring medical and biological topics.

Have Fun Exploring!
-------------------

Enjoy using BioBot and exploring the vast realm of medical and biological knowledge it can provide!
