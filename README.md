# OpenAI DocSearch

This repository contains experiments and implementations using OpenAI, Azure OpenAI, and Azure Cognitive Search APIs to build a conversational AI chatbot application. It is for enabling contextual search and summarization.

## Project Overview
The application leverages OpenAI's Large Language Model (LLM) to enable:

<ol>
<li>Contextual Search: Search through manuals, project tools, and documents to provide specific help on cloud migration issues.</li>
<li>Summarization: Generate summaries of project reports, highlighting key trends, costs, and risks to help project managers deliver concise updates.</li>
</ol>

## Features
<ol>
<li>Experimentation with different LLM Models</li>
<li>Conversational AI: Provides conversational responses to user queries based on relevant documents and manuals.</li>
<li>Contextual Document Search: Uses Azure Cognitive Search to find information across various documents related to cloud migration.</li>
<li>Summarized Insights: Summarizes detailed project information to aid in decision-making and reporting.
Technologies Used</li>
<li>Azure OpenAI GPT Model: For generating responses and processing queries.</li>
<li>Azure Cognitive Search: Enables fast and accurate retrieval of relevant documents and information.</li>
<li>Azure Blob Storage: Stores documents and resources for easy access by the chatbot.</li>
<li>Langchain: Manages interactions between components to create a seamless conversational experience.</li>
<li>Python: The primary language for backend development and data processing.</li>
<li>Flask: Provides the API interface for the chatbot.</li>
<li>Streamlit: A simple web interface for interacting with the chatbot.</li>
<li>ChromaDB: Manages embeddings and stores vectorized representations for efficient document retrieval.</li>