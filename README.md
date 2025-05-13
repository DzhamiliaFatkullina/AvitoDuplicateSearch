# Avito ML Cup 2025 - Duplicate Detection

## Project Structure

- `src/`: Core Python modules for:
  - Data loading (handles Avito's parquet+zip format)
  - Image/text feature extraction
  - Model training
  - Submission generation

- `notebooks/`: Exploration only

## Setup

1. Create virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate # or \venv\Scripts\activate on Windows
   pip install -r requirements.txt
   ```