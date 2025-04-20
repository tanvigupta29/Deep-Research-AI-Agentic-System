# Deep-Research-AI-Agentic-System
The Deep Research AI Agentic System is an intelligent, multi-agent AI architecture designed for automated deep research, analysis, and answer generation from the web. It combines real-time online search, rich content extraction, memory retention via RAG (Retrieval-Augmented Generation), and self-critiquing AI agents to deliver high-quality, well-referenced, and improved answers to user queries.

This system uses:
Tavily Search API for real-time web information
LangGraph and LangChain for orchestrating multiple agents
ChromaDB for storing and retrieving past research
OpenAI LLMs for generating and refining answers
Streamlit for an interactive front-end UI

Features & Workflow:

ResearchAgent:
Searches the web using Tavily.
Extracts full content from search result URLs.
Stores this information in ChromaDB for long-term use.
AnswerAgent:
Synthesizes a detailed response using LLMs.
Enhances the response using previously stored content from ChromaDB (RAG).
CritiqueAgent:
Reviews the answer for quality, accuracy, and clarity.
Refines the response based on internal critique.
Streamlit UI:
Users enter a query.
The system runs all agents and displays the final answer live.


