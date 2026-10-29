# Book Indexing and Search System

A Python project for processing text files and searching for words using the TF-IDF (Term Frequency–Inverse Document Frequency) technique.

## About the Project

This project was developed as part of my academic programming practice. It focuses on text processing and basic information retrieval by analyzing the words contained in one or more text files.

The program calculates word frequencies and TF-IDF scores to help identify how relevant a word is within a collection of documents.

## Features

- Read and process text files.
- Clean words by converting them to lowercase and removing common punctuation.
- Count word occurrences using Python dictionaries.
- Calculate Term Frequency (TF).
- Calculate Inverse Document Frequency (IDF).
- Calculate TF-IDF scores for documents.
- Search for a word and sort matching books by their TF-IDF scores.
- Process a single text file or a folder containing text files.

## Technologies and Concepts

- **Language:** Python
- **Libraries:** `argparse`, `os`, `math`, and `itertools`
- **File handling:** Reading text files and processing their contents.
- **Data structures:** Lists and dictionaries.
- **Information retrieval:** TF, IDF, and TF-IDF.
- **Command-line arguments:** Providing file paths and search terms when running the program.

## Project Structure

```text
python-academic-projects/
├── auxiliary_functions.py
├── indexing.py
└── README.md
```

## Requirements

- Python 3
- Text files (`.txt`) to analyze

The `auxiliary_functions.py` and `indexing.py` files should be located in the same directory.

## How to Run

### 1. Open a terminal

Navigate to the directory containing the Python files.

### 2. Run the program with a text file

```bash
python indexing.py Dracula.txt dracula
```

### 3. Run the program with a folder of text files

```bash
python indexing.py texts dracula
```

Replace `Dracula.txt` or `texts` with the path to your own file or folder. Replace `dracula` with the word you want to search for.

**Note:** The text file or folder must exist at the specified path. The program's output depends on the documents provided.

## What I Learned

While working on this project, I practiced writing reusable Python functions, working with files and directories, organizing data with lists and dictionaries, using command-line arguments, and applying basic TF-IDF calculations for text analysis.

## Author

**Fátima Montoya**  
Information Systems Engineering Student
