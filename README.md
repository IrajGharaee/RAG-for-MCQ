# Multi-Agent RAG System for Scientific Question Answering

## Overview
This project is an **agentic Retrieval-Augmented Generation (RAG)** system designed to answer complex, multiple-choice scientific questions. It combines **Large Language Models (LLMs)** with intelligent multi-agent collaboration and external knowledge retrieval from **Wikipedia** to improve reasoning accuracy.

## Key Features
- **Multi-Agent Architecture:**
  - **Answer Agent:** Generates an initial guess using the LLM.
  - **Rephrasing Agent:** Reformulates the question to improve search quality.
  - **Expansion Agent:** Expands the queries into multiple context-rich search variations.
  - **Retriever Agent:** Uses the **Wikipedia API** to fetch relevant context.
  - **Final Reasoner:** Synthesizes all retrieved information and produces the final answer.
- **Technologies Used:**
  - **LangChain**, **Wikipedia API**, **Python**, **LLM (Llama)**
  - Demonstrates the power of **retrieval-augmented reasoning** in specialized domains

## Goals
- Improve factual accuracy of LLM-generated answers through grounded retrieval
- Explore **agentic AI workflows** and inter-agent communication
- Serve as a foundation for **domain-specific knowledge assistants**
