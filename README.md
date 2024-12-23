# Joseph Krozak (JKK2139), Date: 12/19/2024
# COMS E6998-015 Introduction to Deep Learning and LLM-based Generative AI Systems – Final Project
# From Audio to Actionable: Leveraging ASR and LLMs for Real-Time, 
# Interactive Graph-Based Investigations for Emergency Response

## Description
This project evaluates the performance of GPT-4 and Llama-3.2B models for entity and relationship extraction tasks. It leverages a single Jupyter notebook for ontology loading, prompt generation, and result evaluation.

## Contents
- `E6998-015-Final-Project-Tutorial-Video.mp4`: Now that you're here, make sure to watch this video!
- `20241219-E6998-015-Final-Project.ipynb`: The main Jupyter notebook to conduct all project operations.
- `dev.json, test.json, train.json`: TACRED dataset JSON files this project uses/.
- `*.pkl`: Multiple PKL "gold" files, which contain the results of the runs used in support of the
final project report and presentation.  These are loaded within the Jupyter notebook to visulize
this information 
- `README.md`: This file.

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/robotron-2084/E6998-015.git
2. cd E6998-015
3. Install the following packages: openai, python-dotenv, sentence-transformers, 
pandas, numpy, matplotlib, networkx, 

4. Configure API Access
	a. OpenAI API Key
	
	To use OpenAI GPT-4 features, you need to create a .env file in the root of the repository and include your OpenAI API key:
	
	OPENAI_API_KEY=your_openai_api_key
	
	b. Llama 3.2 Instance
	
	Ensure that you have access to a Llama 3.2 instance running in a llama-stack environment. This is required to execute the Llama-related tests. You will need the endpoint and port of the running instance, which should be correctly configured in your scripts or notebook.
	
5. Run the Jupyter Notebook

To evaluate the project, open the Jupyter notebooks provided in the repository. Start a Jupyter Notebook server:

	jupyter notebook

Then open the project notebook (20241219-E6998-015-Final-Project.ipynb) and step through the cells sequentially.

6. Notes on Execution

	OpenAI-specific tasks will only run if a valid API key is provided in the .env file.

	Tests for Llama 3.2 require a running instance of the model. Ensure the connection details (e.g., endpoint URL, port) are properly configured in the code before running these cells.

	Review and modify any environment-specific paths or configurations as needed.