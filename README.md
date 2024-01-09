# Talking-with-a-database-LLM-project

In this project, I used a made up Tshirt store Rafeeds Tshirts which sells 4 brands of tshirts Nike, Addidas, Levi and Ven Huesen. I have the database table tshirts and discounts which has the dummy data for the store.

In this project, I created a streamlit app that talks with the database, converts the plain text into SQL queries and fetches it back to show the result with the help of Google Palm LLM model. To perform better, I used few shot learning technique to learn the model based on some example queries and the corresponding text prompt.

## Workflow
1. LLM model create
2. database connection to mysql
3. fetch queries from plain text
4. creating few shot dictionaries
5. creating vector embeddings
6. storing vectors in vectorstore
7. creating semantic similarities with the question
8. setting up prompt template with inputs
9. creating new chain with few shots
10. running the app with streamlit

## Use Case
For the industrial setting, a stakeholder of a company who doesn't know SQL can run a detailed prompt in the inpput field and corresponding queries will be created and specified information can be retrieved from database. Decision making will be easier, reporting can be done just like talking with a database.

## Tools and Technology 
1. Google Palm LLM model
2. Mysql Workbench
3. Few Shot learning technique
4. Huggingface embeddings
5. Chromadb for vectorstore
6. Streamlit application
7. Source Control (Git)
8. Conda virtual Environment
9. Standard coding practices