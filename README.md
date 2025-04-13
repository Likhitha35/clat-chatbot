# clat-chatbot
Simple CLAT FAQ chatbot using rule-based and NLP methods

# CLAT Chatbot (Rule-based + NLP)

This project is a simple chatbot that answers questions related to the CLAT exam using both:
- Rule-based logic
- NLP-based similarity using Sentence Transformers (`all-MiniLM-L6-v2`)

## Features
- CLAT eligibility, syllabus, cutoffs, and other FAQs
- Uses sentence-transformers for semantic similarity
- Falls back to rule-based matching when NLP confidence is low

## Technologies
- Python
- `sentence-transformers`
- NumPy
- Regex
- Jupyter Notebook

## Installation
```bash
pip install sentence-transformers numpy
