# solar-challenge-week1

## Project Overview
This repository contains the code and analysis for exploratory data analysis (EDA), data cleaning, and profiling of solar datasets from Benin, Sierra Leone, and Togo. The goal is to understand solar irradiance and weather patterns by analyzing and visualizing the datasets.

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/rediet-teshome123/solar-challenge-week1.git
   cd solar-challenge-week1
Create and activate a Python virtual environment:

python -m venv venv
# Windows
.\venv\Scripts\activate
# macOS/Linux
source venv/bin/activate

Install required packages:
pip install -r requirements.txt

### Folder Structure
notebooks/ – Jupyter notebooks for EDA by country (e.g., benin_eda.ipynb)

data/ – Raw and cleaned CSV datasets

.github/workflows/ – GitHub Actions workflows for CI

scripts/ – Python scripts (if any)

.gitignore – To exclude unnecessary files like venv and data checkpoints

### How to Use
Switch to the appropriate branch (e.g., eda-benin) to work on specific country data.

Run notebooks in notebooks/ to load data, clean it, perform analysis, and visualize results.

Commit and push your changes with meaningful commit messages.

Open a Pull Request to merge changes back into the main branch.
