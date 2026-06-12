# AI Legal Document Analyzer

## Overview

AI Legal Document Analyzer is a Python-based application that analyzes legal agreements and contracts using Large Language Models (LLMs).

Users can upload a PDF agreement, specify the agreement type, and receive a structured analysis including summaries, clauses, risks, obligations, and recommendations.

## Features

- Upload PDF legal documents
- AI-powered agreement analysis
- Extract important clauses
- Detect risky clauses
- Identify missing clauses
- Analyze obligations of parties
- Extract confidentiality terms
- Extract payment and penalty conditions
- Analyze termination clauses
- Generate risk ratings

## Technologies Used

- Python
- LangChain
- OpenRouter API
- GPT-4o-mini
- PyPDF
- Streamlit

## Installation

Install required packages:

```bash
pip install streamlit python-dotenv langchain langchain-community langchain-openai pypdf faiss-cpu qdrant-client
