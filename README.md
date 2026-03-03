#NOTE: due to personal details and api keys, i can't be able to share my code here but i have fully functional code in my system!

#Autonomous AI Sales Agent with RAG Memory
Python, LangGraph, LangChain, FAISS, PostgreSQL, Gmail API, Cohere/Gemini
2026 | Personal SaaS System

Designed and implemented a multi-stage AI sales agent that processes call transcripts, analyzes customer intent, and autonomously decides follow-up actions using structured LLM outputs.

Built a conditional LangGraph workflow to orchestrate transcript analysis, metadata extraction (summary, interest level, next call scheduling), and automated email dispatch.

Integrated Gmail API (OAuth2) to generate and send AI-personalized follow-up emails triggered by conversation context.

Engineered a hybrid memory system combining PostgreSQL (structured call logs and customer status tracking) with FAISS vector embeddings for semantic retrieval across historical interactions.

Developed a Retrieval-Augmented Generation (RAG) pipeline that analyzes customer tone, objections, and decision signals to assist future sales strategy.

Implemented vector storage and retrieval using BGE embeddings with metadata-aware indexing for transcript similarity search.

Built automated lead filtering logic to detect and separate uninterested customers from active sales pipelines.

Designed end-to-end transcript ingestion pipeline supporting parent call threads and follow-up conversations
