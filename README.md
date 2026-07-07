# Generative AI Learning

<p align="center">
  <a href="https://github.com/your-username/generative-ai-learning"><img src="https://img.shields.io/badge/Language-Python-blue.svg" alt="Python" /></a>
  <a href="https://github.com/your-username/generative-ai-learning"><img src="https://img.shields.io/badge/Status-Active-green.svg" alt="Active" /></a>
  <a href="https://github.com/your-username/generative-ai-learning"><img src="https://img.shields.io/badge/LICENSE-MIT-orange.svg" alt="MIT" /></a>
  <br>
  <strong>Embark on your journey into Generative AI with LangChain</strong>
</p>

<br>

## About

This repository serves as a comprehensive learning resource for Generative AI, focusing on LangChain ecosystem implementations. It provides structured notebooks covering fundamental concepts, practical implementations, and advanced techniques for building AI applications with tools, agents, memory, and more.

## Features

- **11 Comprehensive Learning Topics** from LangChain basics to advanced middleware
- **Hands-on Implementation** through Jupyter notebooks with working code examples
- **Modern AI Frameworks** including LangChain, LangGraph, Groq, and Google Gemini integrations
- **Practical Tooling** for building real-world AI applications
- **Production-Ready** code structure following Python best practices

### Key Topics Covered:
1. Introduction to LangChain
2. Chat Models
3. Prompt Engineering
4. Tools
5. Tool Calling
6. AI Agents
7. Multiple Tool Agents
8. Messages
9. Structured Output
10. Memory
11. Middleware

## Repository Structure

```
GENERATIVE-AI/
├── src/
│   ├── 1.Langchain.ipynb
│   ├── 2.Tools.ipynb
│   ├── 3.Agent.ipynb
│   ├── 4.AgentMultipleTools.ipynb
│   ├── 5.messages.ipynb
│   ├── 6.StructuredOutput.ipynb
│   ├── 7.memory.ipynb
│   └── 8.Middleware.ipynb
├── .env
├── .gitignore
├── .python-version
├── main.py
├── pyproject.toml
├── requirements.txt
├── uv.lock
└── README.md
```

## Technologies

| Category | Technology | Purpose |
|----------|------------|---------|
| Core | Python | Primary programming language |
| Framework | LangChain | Core AI application framework |
| Framework | LangGraph | Advanced workflow orchestration |
| Community | LangChain Community | Extended LangChain capabilities |
| Integration | LangChain Groq | GPU-accelerated model hosting |
| Integration | LangChain Google Gemini | Google AI model integration |
| Tooling | python-dotenv | Environment variable management |

## Learning Roadmap

This repository follows a progressive learning path:

1. **Foundation** (Notebooks 1-3): Start with LangChain basics, chat models, and prompt engineering
2. **Tooling** (Notebooks 4-5): Learn tools and tool calling mechanisms
3. **Agents** (Notebooks 6-7): Build AI agents with multiple tools and agent orchestration
4. **Communication** (Notebook 8): Master message handling and structured communication
5. **Advanced** (Notebook 9-12): Implement structured output, memory management, and middleware

The sequence ensures you build from fundamental concepts to sophisticated AI applications step by step.

## Notebooks Overview

| Notebook | Description |
|----------|-------------|
| 1.Langchain.ipynb | Foundation concepts and introduction to LangChain architecture |
| 2.Tools.ipynb | Tool integration patterns and implementation strategies |
| 3.Agent.ipynb | Basic agent creation and execution workflows |
| 4.AgentMultipleTools.ipynb | Advanced multi-tool agent architectures |
| 5.messages.ipynb | Message handling, chaining, and conversation management |
| 6.StructuredOutput.ipynb | Structured output parsing and validation techniques |
| 7.memory.ipynb | Memory implementation and conversation persistence |
| 8.Middleware.ipynb | Custom middleware development and request/response processing |

## Installation

```bash
# Clone the repository
git clone https://github.com/your-username/generative-ai-learning.git
cd generative-ai-learning

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Alternatively, use uv for faster setup
# uv sync
```

## Environment Variables

The project uses `.env` file for configuration. Copy the `.env` file and update these values:

```env
# Groq API Configuration
GROQ_API_KEY=your_groq_api_key_here

# Google Gemini API Configuration
GOOGLE_API_KEY=your_gemini_api_key_here

# Additional environment variables may be added as needed
```

## Running

Start your learning journey by exploring the notebooks:

```bash
# Install JupyterLab for enhanced notebook experience
pip install jupyterlab

# Launch JupyterLab
jupyter lab

# Or use classic Jupyter notebook
jupyter notebook
```

Access the notebooks through the `src/` directory to begin learning and experimenting with the concepts.

## Project Flow

```
User
 ↓
Prompt
 ↓
LLM
 ↓
LangChain
 ↓
Tools
 ↓
Agent
 ↓
Response
```

## Concepts Learned

- **LangChain**: A framework for developing applications powered by language models. It enables building complex AI workflows through modular components like chains, agents, and tools, simplifying the integration of language models into applications.

- **Chat Models**: Foundation models fine-tuned for conversational interactions. These models understand context, maintain conversation flow, and generate human-like responses, forming the core of interactive AI applications.

- **Prompt Templates**: Structured templates for crafting effective model prompts. They provide consistency, reduce prompt engineering errors, and enable reusable question-answering patterns across different use cases.

- **Messages**: Data structures representing conversation turns. Messages carry context, history, and system instructions, enabling agents to maintain coherent multi-turn conversations and understand their operational context.

- **Tools**: Modular functionalities that extend AI agent capabilities. Tools like web search, database queries, or calculations allow agents to perform complex tasks by breaking them into manageable components.

- **Tool Calling**: The mechanism where AI models autonomously select and invoke tools to accomplish tasks. This enables dynamic problem-solving by allowing agents to access external resources and perform actions beyond pure language generation.

- **Agents**: Autonomous systems that plan, reason, and take action using tools and language models. Agents coordinate multiple components to achieve complex goals through iterative decision-making and tool utilization.

- **Structured Output**: Formatted data responses ensuring consistency and predictability. Structured outputs transform unstructured language model responses into actionable, machine-readable data formats like JSON or XML.

- **Memory**: Persistent state management enabling context retention across interactions. Memory systems store conversation history, preferences, and learned information, allowing agents to maintain awareness and continuity over time.

- **Middleware**: Intermediary components processing requests before reaching the main application. Middleware handles logging, authentication, error handling, and transformation, ensuring robust and secure AI application operations.

## Future Learning

- **RAG (Retrieval-Augmented Generation)**: Combine knowledge retrieval with generation for more accurate and up-to-date responses
- **Embeddings**: Vector representations of text data enabling semantic similarity search and information retrieval
- **Vector Databases**: Specialized databases storing and querying high-dimensional vector embeddings efficiently
- **LangGraph**: Advanced workflow orchestration with state management and conditional routing
- **Multi-Agent Systems**: Coordinated teams of specialized agents working together on complex problems
- **MCP (Model Context Protocol)**: Standardized protocol for agent-model communication and context sharing
- **AI Workflows**: Automated pipelines orchestrating multiple AI components and services
- **AI Applications**: Building production-ready AI products with scalability, reliability, and user experience in mind

## Best Practices

1. **Environment Isolation**: Always use virtual environments to prevent dependency conflicts
2. **API Key Security**: Store sensitive keys in `.env` files and add them to `.gitignore`
3. **Input Validation**: Sanitize user inputs to prevent injection attacks and unexpected behavior
4. **Rate Limiting**: Implement request throttling to avoid API quota exhaustion
5. **Error Handling**: Use try-catch blocks and provide meaningful error messages
6. **Logging**: Implement comprehensive logging for debugging and monitoring
7. **Testing**: Write unit tests for critical functions and data processing pipelines
8. **Documentation**: Maintain clear README files and inline comments
9. **Version Control**: Use semantic versioning for releases and maintain changelog
10. **Resource Management**: Monitor memory usage and implement proper cleanup procedures

## Resources

- **[LangChain Documentation](https://python.langchain.com/docs)**: Official documentation and guides
- **[LangGraph Guide](https://python.langchain.com/docs/langgraph)**: Advanced workflow orchestration
- **[Groq Documentation](https://console.groq.com/docs)**: GPU-accelerated AI model information
- **[Google Gemini API](https://ai.google.dev/gemini-api/docs)**: Google's conversational AI APIs
- **[Python Official](https://docs.python.org/3/)**: Python language reference and tutorials

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Author

Name: [Suraj Gupta]
GitHub: surajgupta001
