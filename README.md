# Semantic Spotter

Semantic Spotter is a Retrieval-Augmented Generation (RAG) application designed to efficiently search and answer questions from insurance policy documents. This project leverages LangChain and GPT-3.5-turbo for its functionality.

## Table of Contents
- [General Info](#general-information)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Deployment](#deployment)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)



## General-information

 **Problem Statement**

  We are provided with a Insurance policy documents which are given in the form of pdf files. Goal here is to build a simple RAG application on the provided policy pdf document.

  * **Solution Strategy -** Build a POC which should solve the following requirement:

    * Users would get responses from the Insurance policy document.

  * **Goal -** Solving the above the above requirement in the POC would ensure that the accuracy of the overall model is good and therefore further improvisations and customizations make sense.

  * **Data Used -** Insurance Policy document in pdf formate stored in a single folder.

  * **Tools used -** LangChain has been used.

The main goal of this project was to build a smart system that can search through documents and give clear, helpful answers to questions.

 It combines two powerful tools:
   * 	**LangChain** 
   * 	**GPT-3.5-turbo openai model** 


This system was designed to answer questions specifically related to insurance policy documents.


## Prerequisites

Before you begin, ensure you have met the following requirements:

- Google Colab account
- Python 3.x installed
- Required libraries:
  - `langchain`
  - `openai`

## Installation

Install the required libraries:

!pip install -q openai langchain chromadb faiss-cpu PyPDF tiktoken docarray langchain-openai langchain-community


## Usage

Open your Google Colab notebook where the Semantic Spotter program is implemented.

Load your documents (e.g., insurance policies) into the environment by pointing it to the right directory path where these documents are stored on Google Drive. 
Ensure they are in a format that your program can read (e.g., PDF).

Run the code and replace your question in query variable and pass it to rag_chain.invoke() for answer


## Deployment
To deploy this application:

Ensure that your Google Colab environment is set up and all dependencies are installed.

Share the Colab notebook with users or export it as a Python script for local execution.

By using Flask or Streamlit we can creata a user-friendly interface.


## Conclusion
This project built an efficient query engine that quickly finds relevant information from documents and combines it with the conversational power of GPT-3.5-turbo with LangChain framework.

## Acknowledgements
- Content from UpGrad and online articles

## Contact
Created by @Aswani-ReddyKV - feel free to contact!


