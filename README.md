# Text-to-SQL GenAI

This project demonstrates how to use GenAI (LLMs) to convert natural language questions into SQL queries and execute them on a MySQL database.

## Features

- Converts user questions into SQL using LLMs (OpenAI or Gemini)
- Executes generated SQL on a MySQL database
- Jupyter notebook workflow for easy experimentation
- Includes sample data for testing

## Folder Structure

- `text_to_sql.ipynb` – Main Jupyter notebook with all code and workflow
- `data/` – Folder for your database files or CSVs

## Setup

1. Clone this repo and navigate to the folder:
git clone <your-repo-url> cd text-to-sql


2. Install dependencies:
pip install -r requirements.txt

or install manually: langchain, pymysql, openai, google-generativeai, etc.

3. Set up your MySQL database and update connection details in the notebook.

4. (Optional) Get your API keys for OpenAI or Gemini and add them in the notebook.

## Usage

- Open `text_to_sql.ipynb` in Jupyter Notebook or JupyterLab.
- Run the cells step by step:
- Connect to your MySQL database
- Load schema and data
- Use LLMs to generate SQL from questions
- Execute and display results

## Example

Ask a question like:
What was the budget of Product 12?

The notebook will generate the SQL, run it, and show you the result.

## Notes

- Don’t commit API keys or sensitive data.
- For large datasets, consider using Git LFS for versioning.
- You can adapt the notebook to use other LLMs or databases.


