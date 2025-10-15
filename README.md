# Flashcards-AI

An interactive Jupyter notebook that uses AI (e.g. OpenAI) to generate flashcards for study. You can feed it content (text, documents, etc.), and it produces question-answer pairs or flashcards to help reinforce learning.

## Features

- Input arbitrary text or documents and have the notebook generate flashcards (questions + answers).  
- Use prompt engineering / AI model calls to structure the flashcards.  
- Supports customizing parameters (e.g. number of cards, difficulty, etc.).  
- Exploratory and educational: you can inspect, tweak, and extend the logic in the notebook.

## Requirements

- Python 3.x  
- Jupyter / JupyterLab or other notebook environment  
- OpenAI API credentials (or other language model API)  
- Required Python packages (you can install from `requirements.txt` or via pip):

```text
openai
pandas
tqdm
...
