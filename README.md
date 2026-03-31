# Social Media Analytics: Assignment 2: Bipartite Network Analysis

**Course:** MSBA Social Media Analytics (Spring 2026)

## Overview

This project analyzes a Goodreads book review dataset by constructing and analyzing a bipartite network connecting books and reviewers. The goal is to understand review patterns, community structure, and relationships within the reading community using graph-theoretic methods.

## Key Tasks

- **Task B — Bipartite Network Construction:** Build a bipartite graph linking books to reviewers using NetworkX, with filtering to manage density and improve computational efficiency
- **Task C — Network Visualization:** Visualize the bipartite network and analyze its structural properties
- **Task D — Community Detection & Analysis:** Apply network analysis algorithms to uncover communities and reviewer behavior patterns

## Dataset

`goodreads_data.csv` contains scraped Goodreads review data with the following key fields:
- `book_title` - title of the reviewed book
- `reviewer_id` - unique identifier for the reviewer
- Additional review metadata (ratings, text, etc.)

## Files

| File | Description |
|------|-------------|
| `Assignment_TaskBCD.ipynb` | Main analysis notebook covering Tasks B, C, and D |
| `goodreads_data.csv` | Goodreads book-reviewer dataset |
| `Assignment 2 SMA S2026.docx` | Original assignment instructions |

## Technologies

- Python (pandas, networkx, matplotlib)
- Jupyter Notebook / Google Colab

## How to Run

1. Install dependencies: `pip install pandas networkx matplotlib`
2. Open `Assignment_TaskBCD.ipynb` in Jupyter or Colab
3. If running locally, update any hardcoded file paths to point to `goodreads_data.csv`
4. Run all cells top to bottom
