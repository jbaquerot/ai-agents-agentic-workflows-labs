# Building AI Agents and Agentic Workflows - Lab Projects

This repository contains lab exercises and projects from the Building AI Agents and Agentic Workflows Specialization.

## Project Overview

Interactive tool-calling agents built with LangChain that demonstrate:
- Custom tool creation and integration
- LLM-powered dynamic function calling
- Multi-tool agent architectures
- Real-time conversational AI with tool capabilities

## Contents

- `03_Interactive Tool-Calling Agent-v1.ipynb` - Interactive agent with arithmetic and tip calculation tools

## Setup

### Prerequisites

- Python 3.12+
- pip

### Installation

```bash
# Install dependencies
pip install langchain==0.3.25 langchain-openai==0.3.19 langchain-mistralai python-dotenv
```

### Configuration

Create a `.env` file in the project root with your API keys:

```env
OPENAI_API_KEY=your_openai_api_key
MISTRAL_API_KEY=your_mistral_api_key
```

## Usage

Open the Jupyter notebooks and follow along with the exercises.

## Tools Implemented

- **add**: Basic addition of two integers
- **subtract**: Basic subtraction of two integers
- **multiply**: Basic multiplication of two integers
- **calculate_tip**: Calculate tip amount based on bill and percentage

## License

Educational project - part of AI Agents and Agentic Workflows Specialization

## Author

Carlos - AI/ML Learning Journey 2026
