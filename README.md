# LLM Quiz Game

A simple command-line quiz game that uses a local LLM to generate questions and check answers.

## Features

- Generate multiple-choice questions
- Answer questions through the terminal
- Calculate quiz scores
- Save high scores locally

## Tech Stack

- Python
- Ollama for running local language models
- Hugging Face Transformers (planned)
- scikit-learn (planned)

## Setup

### Prerequisites

- Python 3.11 or later

- Git

- Ollama (if using the Ollama backend)

### Installation

1. Clone the repository:

   git clone <your-repository-url>

   cd Local_LLM_QuizGame

2. Create a virtual environment:

   python3 -m venv venv

   source venv/bin/activate

3. Install the dependencies:

   pip install -r requirements.txt

4. Download a model using Ollama:

   ollama pull qwen3:4b

5. Run the application:

   python main.py

## How It Works

1. Choose a topic for the quiz.

2. Generate questions using a local LLM.

3. Answer the questions in the terminal.

4. Check your answers and view your score.

5. Save your high scores for later.

## Future Improvements

- Add difficulty levels

- Support different local models

- Improve answer checking

- Save quiz history

- Add unit tests

## License

No license has been selected yet.
