## TechGPT

05/06/2025
UNC Charlotte
ITCS 5010 : Design and Development of Generative AI Applications
Group 2: Cameron Detig, Zaid Jebril, Sri Girija Naga Anuhya Samudrala, Derek Smith

- Reads a database of prior user queries and llm responses.
- Uses queries to generate a new response using hidden chain of thought. 
- Evaluates the new response using ragas metrics.

Steps to use:

Create virtual environment and install everything in the requirements.txt

Create a .env file and add your DATABRICKS_TOKEN and DATABRICKS_HOST API keys.

In this directory add a .index vector database file, a .parquet metadata file, and a .csv file of test queries.
Assign their file names to the variables below.
