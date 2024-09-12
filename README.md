# RAG to answer football related questions from Wikipedia articles
This folder contains code for retrieving and answering questions about football teams using Wikipedia articles.

## Overview
The goal of this code is to perform RAG. 

The code retrieves Wikipedia articles for the top Premier League football teams, processes them into chunks, extracts embeddings, stores the embeddings in a Chroma vectorstore, and sets up a question-answering pipeline. Users can input questions about these football teams, and the system will provide relevant answers based on the context of the Wikipedia articles. It leverages a local llama 3 model with the help of Ollama.

## Code Structure
wikipedia_rag.ipynb: Main notebook for running the question-answering system.
README.md: This file providing an overview of the project and instructions.
requirements.txt: This file lists all the dependent libraries that can be install with pip. Note: It also contains a lot of the libraries that come pre-installed with a miniconda environment (so not all of these might be necessary)

## Additional Notes
You will need to have ollama installed on your server to be able to run this code.

## License
This project is licensed under the  GNU GENERAL PUBLIC LICENSE - see the LICENSE file for details.

## Acknowledgments
This project utilizes the Ollama library for making use of the llama 3 model offered by Meta.
Wikipedia articles provide the context for answering football-related questions.

