# Multi-Agent AI Orchestration System

A multi-agent AI system that simulates role-based agents (e.g., Principal Investigator, Data Scientist) to collaboratively solve tasks using structured multi-round discussions.

---

## Overview

This project implements a stateful multi-agent orchestration framework where agents interact in structured workflows to analyze problems, exchange insights, and generate consolidated outputs.

The system supports both **team-based meetings** and **individual critique loops**, enabling coordinated reasoning across multiple agents.

---

## Key Features

- Multi-agent system with role-based agents (team lead + members)
- Structured multi-round discussion workflow
- Stateful interaction using threaded conversations
- Tool integration (e.g., PubMed search support)
- Automatic summarization and discussion logging
- Token usage tracking and cost estimation

---

## How It Works

1. Agents are initialized with roles, goals, and expertise  
2. A meeting is created with an agenda  
3. Agents interact across multiple rounds  
4. Each agent contributes based on role-specific prompts  
5. Final output is synthesized and saved  

---

## Tech Stack

- Python  
- OpenAI API (LLM-based agents)  
- REST APIs (PubMed integration)  
- tqdm (progress tracking)  

---

## How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt
```

2. Set your API key:
```bash
export OPENAI_API_KEY=your_api_key
```

3. Run the system:
  ```bash
python run_meeting.py
```

Sample Output
A full example of multi-agent discussion and generated insights:
👉 [View Sample Output](./sample_output.md)




