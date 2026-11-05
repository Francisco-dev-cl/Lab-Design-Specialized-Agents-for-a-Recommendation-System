# Lab: Design Specialized Agents for a Recommendation System

This repository contains an advanced multi-agent artificial intelligence laboratory project focused on designing, structuring, and coordinating specialized AI agents to power a personalized recommendation system.

## 🎯 Project Objective

The goal of this lab is to move beyond simple, single-prompt AI interactions and build a multi-agent system. By decoupling tasks into dedicated, autonomous agents (such as user profiling agents, data filtering agents, and ranking agents), the application choreographs complex logical workflows where agents communicate, pass data tokens, and work together to deliver hyper-personalized user recommendations.

## 📁 Repository Structure

* **`M3L1_Design_Specialized_Agents.ipynb`**: The primary interactive Jupyter Notebook containing the complete architectural pipeline. It covers agent role definitions, system instructions, tool integration parameters, and multi-agent orchestration execution blocks.

## 🛠 Technologies Used

* **Language Core:** Python 3.x
* **Core Environment:** Jupyter Notebooks
* **Multi-Agent Frameworks:** LangChain (Agents/Tools), CrewAI, Autogen, or Watsonx Orchestrate wrappers
* **Generative Core Engines:** Large Language Models (OpenAI API / IBM watsonx.ai microservices)

## 🚀 Installation and Execution

### Local Environment Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Lab-Design-Specialized-Agents-for-a-Recommendation-System
   ```

2. **Install required agent and machine learning packages:**
   Ensure your local virtual environment possesses the tools required for orchestrating agentic structures:
   ```bash
   pip install notebook langchain openai requests
   ```

3. **Launch the development environment:**
   ```bash
   jupyter notebook
   ```

4. **Run the agentic workflow:**
   Open `M3L1_Design_Specialized_Agents.ipynb` from your web dashboard and execute the cells sequentially to witness agent interaction logs.

## 📈 Demonstrated Skills

* **Agentic System Architecture:** Designing decoupled multi-agent ecosystems with precise behavioral guardrails, distinct personas, and clear system mandates.
* **Collaborative AI Orchestration:** Coordinating sequential or hierarchical task routing to pass structured data payloads smoothly between separate AI entities.
* **Intelligent Recommendation Logic:** Leveraging generative feedback loops and custom prompt schemas to parse user preferences and output relevant recommendations.
