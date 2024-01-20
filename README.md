# Shakti - A Substation Asset Maintenance Chatbot 💬

Shakti was the solution build to solve the below problem statement, It is a retrieval augmented generation (RAG)  based LLM powered chatbot which can answer queries of substation workers related to various equipment maintenance process, testing of these equipment, or safety measures, etc.  

### Selected Problem Statement:
**Problem Statement ID:**  SIH1380

**Problem Statement Title:** lntelligent chatbot to answer queries pertaining to various Maintenance Processes within Substation  

**Problem Statement Description:**
	
Substation Asset Maintenance includes various maintenance activities for various equipment classes such as Transformer, Reactors, Circuit Breaker, lnstrument Transformers, Surge Arrestors etc. Maintenance activity for all these equipments include carrying out various tests and checks for which procedures along with acceptable limits are documented. Need is for creating an intelligent chatbot based on natural language processing which may aid in answering user queries pertaining to various maintenance activities. Examples of such queries include steps to carry out a test, its probable values/ acceptable limits, actions to resolve any issue faced during maintenance. The chatbot should have features for semantic processing of queries. It should also includes industrial standards and safety guidelines and test equipment to follow that activity.


## Tech Stack
* Large Language Model: Mistral 7B Instruct v0.1 [[Link]](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.1)
* Embeddings: BAAI/bge large english [[Link]](https://huggingface.co/BAAI/bge-large-en)
* Language model integration framework - LangChain
* Vector Database: ChromaDB
* Django - Web Framework for Python
* Front-end: Bootstrap

## Setting/Installation:
* Run the following command in cmd:
```
pip install -r requirements.txt
```
* Create a file named `.env` in the root directory, add your [hugging face access token](https://huggingface.co/settings/tokens) and save it:
```
SECRET_KEY = YOUR_HF_TOKEN
```

* Now start the server by running the following:
```
python manage.py runserver
```

## Flowchart:
![alt text](https://github.com/zerothrohit/shakti-sih/blob/main/Substation%20Chatbot%20Flowchart.png "Chatbot Flowchart") 

## System Demonstration:

[![Your Video](https://img.youtube.com/vi/TbUXT1-7m1s/0.jpg)](https://youtu.be/TbUXT1-7m1s?si=_w7q3GDI0Vsk-tLi)

