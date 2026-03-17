# LangGraph Long-Term Agent Memory

An agentic email assistant built using LangGraph that incorporates long-term memory to enable personalized, context-aware decision-making over time.

This system demonstrates how agents can evolve by storing and retrieving user preferences, past interactions, and optimized instructions using semantic, episodic, and procedural memory.

---

## Overview

The agent processes incoming emails and decides whether to:

- Ignore low-priority emails  
- Respond with generated replies  
- Notify the user when attention is required  

The system continuously improves by learning from past interactions and updating its memory store.

---

## Architecture

The agent is built using LangGraph workflows with:

- Routing logic for email triage  
- Tool-based actions (write, schedule, notify)  
- Memory store for long-term context  
- Iterative decision-making based on past behavior  

### Memory Types

- **Semantic Memory**: Stores facts and user preferences for retrieval across sessions  
- **Episodic Memory**: Uses past examples to guide decision-making and improve routing  
- **Procedural Memory**: Optimizes system prompts to refine agent behavior over time  

---

## Project Structure

### 1. Baseline Email Assistant  
Implements a basic agent that routes emails and performs actions without long-term memory.

### 2. Email Assistant with Semantic Memory  
Adds persistent memory store to learn and retrieve user preferences and facts.

### 3. Email Assistant with Semantic + Episodic Memory  
Enhances routing decisions using past interaction examples and learned preferences.

### 4. Email Assistant with Semantic + Episodic + Procedural Memory  
Introduces adaptive system prompts to refine agent behavior based on feedback over time.

---

## Agent Workflow

1. Receive incoming email  
2. Route email based on intent and priority  
3. Retrieve relevant memory (if available)  
4. Decide action: ignore, respond, or notify  
5. Execute tool (response generation or scheduling)  
6. Update memory store with new information  

---

## Setup

Clone repository:

git clone https://github.com/your-username/LangGraph-Long-Term-Agent-Memory.git  
cd LangGraph-Long-Term-Agent-Memory  

Install dependencies:

pip install -r requirements.txt  

Set environment variables:

export OPENAI_API_KEY=your_key_here  

---

## Running the Project

Launch notebooks:

jupyter notebook  

Run notebooks sequentially to observe memory evolution and agent improvement.

---

## Key Concepts

- Long-term memory in agentic systems  
- Memory retrieval and storage mechanisms  
- Personalized agent behavior through learning  
- Workflow orchestration using LangGraph  
- Tool-augmented decision-making  

---

## Use Cases

- Personal email assistants  
- Productivity automation systems  
- Customer support agents with memory  
- Personalized AI copilots  

---

## Future Improvements

- Add evaluation metrics for decision accuracy  
- Introduce vector-based memory retrieval  
- Enable real-time streaming workflows  
- Deploy as a scalable API service  

---

## Tech Stack

- Python  
- LangGraph  
- LangChain ecosystem  
- OpenAI APIs  
- Jupyter Notebooks  

---

## Summary

This project demonstrates how to build agents that do not just respond, but learn, adapt, and improve over time using structured long-term memory.
