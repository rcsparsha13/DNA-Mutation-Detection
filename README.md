# DNA-Mutation-Detection
DNA Sequence Mutation Detection - DAA Project
# Genomic Shield: Intelligent DNA Threat Screening System

## Project Overview

Genomic Shield is a Design and Analysis of Algorithms (DAA) project that explores efficient screening of DNA sequences against a reference watchlist. It combines string-matching techniques and sequence-alignment algorithms to identify exact matches and analyze sequence variations.

The project includes a software dashboard designed to display screening results, sequence similarity information, and visual representations of alignment computations.

## Problem Statement

Searching large DNA sequences using simple character-by-character comparisons can be computationally expensive. Additionally, exact matching alone may fail to identify sequences containing substitutions, insertions, or deletions.

Genomic Shield explores algorithmic techniques for efficient pattern searching and sequence alignment to address these challenges.

## Objectives

- Implement efficient DNA sequence pattern searching.
- Explore indexing structures for faster sequence lookup.
- Apply string-matching algorithms to identify sequence patterns.
- Use dynamic programming to compare DNA sequences.
- Analyze sequence similarity and potential mutations.
- Visualize screening results through an interactive dashboard.

## Algorithms Used

### 1. Suffix Trie
An indexing structure used to support efficient pattern searching in DNA sequences.

### 2. Boyer–Moore String-Matching Algorithm
A pattern-matching algorithm that uses character-shifting rules to skip unnecessary comparisons.

### 3. Needleman–Wunsch Algorithm
A dynamic programming algorithm used for global alignment of two sequences.

### 4. Smith–Waterman Algorithm
A dynamic programming algorithm used for local sequence alignment to identify matching subsequences.

## Technologies Used

According to the project report:

- Python
- NumPy
- Streamlit
- Matplotlib
- Seaborn
- JSON for reference data storage

## Methodology

The proposed system follows a multi-stage screening process:

1. **Sequence Input:** Accept DNA sequence data for analysis.
2. **Preprocessing:** Normalize the input sequence and remove unwanted formatting.
3. **Pattern Matching:** Search for matching patterns using string-matching algorithms.
4. **Sequence Alignment:** Compare sequences using global and local alignment techniques.
5. **Result Classification:** Evaluate similarity scores against configured thresholds.
6. **Visualization:** Display screening results and alignment information through the dashboard.

## Applications

Potential application areas include:

- Educational study of DNA sequence algorithms.
- Computational biology research and experimentation.
- Demonstration of string matching and dynamic programming.
- Exploration of genomic screening concepts.



## Project Scope

This project is an academic prototype for studying algorithmic DNA sequence screening. Its results should not be treated as validated biological threat assessments or as a substitute for professional biosecurity screening systems.

<img width="954" height="496" alt="image" src="https://github.com/user-attachments/assets/faf95506-b70b-47e4-b5c7-e58dd9433fcb" />
