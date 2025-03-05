# Plagiarism Checker

## Project Overview
The **Plagiarism Checker** is a Python-based project designed to detect plagiarism among documents. The program compares the contents of these files and provides a similarity score to determine potential instances of copied content.

## Features
- Reads and processes multiple text files.
- Compares text documents using similarity detection algorithms (e.g., cosine similarity, Jaccard similarity, or Levenshtein distance).
- Generates a plagiarism percentage report.
- Highlights matching sections between files.

## Installation
To use this project, ensure you have Python installed on your system. Then, install the required dependencies using:
```sh
pip install -r requirements.txt
```

## Usage
Run the script with the following command:
```sh
python plagiarism_checker.py
```

### Input
- Three text files: `om.txt`, `aayush.txt`, `bhadrik.txt`.

### Output
- A similarity percentage for each pair of documents.
- A report highlighting possible plagiarized sections.

## Methodology
The project utilizes Natural Language Processing (NLP) techniques to compare text similarity. Common approaches include:
1. **Tokenization & Preprocessing** - Removing punctuation, stopwords, and converting text to lowercase.
2. **Vectorization** - Converting text into numerical representations.
3. **Comparison Algorithms**:
   - Cosine Similarity (TF-IDF or Count Vectorizer)
   - Jaccard Similarity
   - Levenshtein Distance (Edit Distance)

## Example Output
```
Plagiarism Report:
----------------------------------
Similarity between om.txt and aayush.txt: 14%
Similarity between om.txt and bhadrik.txt: 18%
Similarity between aayush.txt and bhadrik.txt: 54%
----------------------------------
Potentially plagiarized sections highlighted in report.txt.
```

## Future Enhancements
- Implement GUI for better user experience.
- Support for more file formats (PDF, DOCX, etc.).
- Integration with a database for storing results.
- Improved NLP techniques for better accuracy.

## Contributors
Om Doshi

Github: OmDoshi13


