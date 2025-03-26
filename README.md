# Book Recommender

This project is a **semandtic book recommender** that uses machine learning and natural language processing to recommend books based on user input. It features a web-based dashboard built with [Gradio](https://gradio.app/) for an interactive user experience.

## Features

- **Semantic Search**: Uses embeddings from Hugging Face's `sentence-transformers` to find books similar to a user-provided query.
- **Emotion-Based Recommendations**: Allows users to filter recommendations based on emotional tones like "Happy," "Sad," or "Suspensful."
- **Category Filterings**: Users can filter books by categories such as fiction, non-fiction, etc.
- **Interactive Dashboard**: Built with Gradio for a user-friendly interface.

## Installation

1. Clone the repository:
```bash
git clone https://github.com/minhphung152/book-recommender.git
cd book-recommender
```

2. Create a virtual environment and activate it:
```bash
python3 -m venv .venv
source .venv/bin/activate
```

3. Install the required dependencies:
```bash
pip isntall -r requirements.txt
```

## Usage

1. Run the Gradio dashboard:
```bash
python gradio-dashboard.py
```

2. Open the dashboard in your browser (usually at http://127.0.0.1:7860).

3. Enter a description of a book, select a category, and choose an emotional tone to get recommendations.