# Hierarchical Multi-Agent Coding Assistant

A hierarchical multi-agent system that can automate software development tasks, from requirements gathering to deployment, leveraging large language models and agent frameworks.

## Project Overview

This system uses a hierarchical structure of specialized agents to handle different aspects of software development:
- Project Manager Agent: Coordinates tasks and manages the development workflow
- Architect Agent: Designs system architecture and API contracts
- Backend Agent: Implements server-side logic
- Frontend Agent: Generates UI code
- QA Agent: Creates and runs tests
- DevOps Agent: Handles deployment and CI/CD
- Documentation Agent: Generates project documentation

## Setup

1. Clone the repository:
```bash
git clone https://github.com/Bladxn/hierarchical-coding-assistant.git
cd hierarchical-coding-assistant
```

2. Create a virtual environment:
```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Create a `.env` file and add your LLM API key:
```
LLM_API_KEY=your_api_key_here
```

## Development

- Source code is in the `src/` directory
- Tests are in the `tests/` directory
- Documentation is in the `docs/` directory

## License

[MIT License](LICENSE) 