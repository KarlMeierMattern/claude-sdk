# Claude SDK

Python tutorial for the <a href="https://anthropic.skilljar.com/claude-with-the-anthropic-api" target="_blank" rel="noopener noreferrer">Anthropic API</a>.

## Setup

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install anthropic python-dotenv
```

Create `.env` with your API key:

```
ANTHROPIC_API_KEY=your_key_here
```

## Usage

Open `main.ipynb` in Jupyter and run the cells. The notebook covers:

- Basic message API (user/assistant turns)
- Multi-turn conversation with history
- System prompts
- Interactive chatbot loop

## Requirements

- Python 3.10+
- Anthropic API key
