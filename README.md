# Building AI Agents and Agentic Workflows - Lab Projects

Lab exercises from the Building AI Agents and Agentic Workflows Specialization.

## Project Structure

```text
99_Labs/
├── src/                  # Python modules used by notebooks
│   ├── leftover.py       # CrewAI @CrewBase class for leftover management
│   └── config/
│       ├── agents.yaml   # CrewAI agent definitions
│       └── tasks.yaml    # CrewAI task definitions
├── data/                 # Input datasets
│   ├── classification-dataset.csv
│   └── regression-dataset.csv
├── outputs/              # Generated agent outputs (gitignored)
├── 01_Hello World-v1.ipynb
├── 02_LLM-Powered Data Science-v1.ipynb
├── 03_Interactive Tool-Calling Agent-v1.ipynb
├── 04_Tool-Calling-v1.ipynb
├── 05_chat-with-your-dataframe-using-langchain-v1.ipynb
├── 06_LangGraph101-v1.ipynb
├── 07_Tweet-Reflection-Agent-v1.ipynb
├── 08_Reflexion Agent-v1.ipynb
├── 09_ReAct-v1.ipynb
├── 10_design-patterns-v1.ipynb
├── 11_CrewAI-101-v1.ipynb
└── 12_Create a Structured Meal Grocery Planner with CrewAI.ipynb
```

## Notebooks

| # | Notebook | Topic |
| --- | -------- | ----- |
| 01 | Hello World | LangChain tool calling basics |
| 02 | LLM-Powered Data Science | AI-assisted data analysis |
| 03 | Interactive Tool-Calling Agent | Multi-tool agent architectures |
| 04 | Tool Calling | Function calling with LLMs |
| 05 | Chat with DataFrame | Natural language to charts with LangChain |
| 06 | LangGraph 101 | Stateful AI workflows |
| 07 | Tweet Reflection Agent | Reflection pattern with LangGraph |
| 08 | Reflexion Agent | External knowledge integration |
| 09 | ReAct | Reasoning + acting with LangGraph |
| 10 | Design Patterns | Workflow patterns with LangGraph |
| 11 | CrewAI 101 | Multi-agent systems with CrewAI |
| 12 | Meal Grocery Planner | Structured outputs + multi-agent CrewAI |

## Setup

### Prerequisites

- Python 3.12+
- Virtual environment (`.venv/`)

### Installation

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt   # or follow per-notebook install cells
```

### Configuration

Create a `.env` file in the project root:

```env
OPENAI_API_KEY=your_openai_api_key
MISTRAL_API_KEY=your_mistral_api_key
SERPER_API_KEY=your_serper_api_key
TAVILY_API_KEY=your_tavily_api_key
```

## Usage

Open any notebook from the project root and run cells top-to-bottom. Each notebook is self-contained and installs its own dependencies in the first cell.

## Author

Carlos - AI/ML Learning Journey 2026
