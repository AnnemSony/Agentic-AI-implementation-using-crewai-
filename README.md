
```markdown
# Agentic AI Implementation using Crewai

This repository implements an Agentic AI system utilizing Crewai, Google Gemini 1.5 Flash, SerperDev Tool, and Langchain.

## Project Description

This project aims to uncover groundbreaking technologies and narrate compelling tech stories using AI agents. The agents are built to perform research and write articles on specified topics using advanced language models and tools.

## Files

- `agents.py`: Defines the AI agents with specific roles such as a Senior Researcher and a Writer, equipped with memory and delegated capabilities.
- `crew.py`: Forms a tech-focused crew and starts the task execution process with enhanced feedback.
- `tasks.py`: Contains tasks assigned to the AI agents, including research and writing tasks with detailed descriptions and expected outputs.
- `tools.py`: Initializes and configures the SerperDev tool for internet searching capabilities.
- `requirements.txt`: Lists all dependencies required to run the project.

## Installation

To install the required dependencies, run:
```bash
pip install -r requirements.txt
```

## Usage

1. **Initialize the Environment:**
   Ensure you have a `.env` file with the necessary API keys, such as `GOOGLE_API_KEY` and `SERPER_API_KEY`.

2. **Run the Agents:**
   Execute the `agents.py` script to initialize the agents.
   ```bash
   python agents.py
   ```

3. **Assign Tasks:**
   Use the `tasks.py` script to assign tasks to the agents.
   ```bash
   python tasks.py
   ```

4. **Form the Crew and Kickoff:**
   Use the `crew.py` script to form the crew and start the task execution process.
   ```bash
   python crew.py
   ```

## Dependencies

The project relies on various Python packages listed in the `requirements.txt`. Some key dependencies include:
- `crewai`
- `langchain`
- `google-auth`
- `fastapi`
- `serper`

## Contributing

Feel free to open issues or submit pull requests for improvements and new features.

## License

This project is licensed under the MIT License.
```

You can copy and paste this content directly into your `README.md` file on GitHub.
