## TechGPT
AI Assistant to answer domain specific questions using RAG. Utilizes ChatGPT-4o with hidden chain of thought and RAGAs to evaluate responses.


05/06/2025
UNC Charlotte
ITCS 5010 : Design and Development of Generative AI Applications

Group 2: Cameron Detig, Zaid Jebril, Sri Girija Naga Anuhya Samudrala, Derek Smith

- Reads a csv database of prior user queries and llm responses from a previous system.
- Uses queries to generate new responses using prompt enhancement and hidden chain of thought. 
- Evaluates the new responses using ragas metrics to measure faithfulness, answer relevancy, context recall, and context precision.

Steps to use the code:

Create a virtual environment and install everything in the requirements.txt

Create a .env file and add your DATABRICKS_TOKEN and DATABRICKS_HOST API keys.

In the same directory as the TechGPT.ipynb file, add a .index vector database file, a .parquet metadata file, and a .csv file of test queries.
Assign their file names to the variables in the first cell of the notebook.
