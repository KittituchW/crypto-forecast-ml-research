# AMLA_AT1_Group3: NBA Draft Prediction

This project is part of the 36120 Advanced Machine Learning Application subject at UTS (Spring 2025).  
It aims to predict whether a college basketball player will be drafted into the NBA based on player statistics.

## Project Structure

This project follows the Cookiecutter Data Science structure:
adv_mla_lab_1/
├── data/              # Raw and processed data files (not tracked by git)
├── models/            # Trained models
├── notebooks/         # Experiment notebooks (see naming format below)
├── github.txt         # Link to this repo (for submission)
├── pyproject.toml     # Poetry environment and dependencies
└── README.md          # You’re reading this file

## Environment Setup

1. Install Python 3.11.4 using pyenv

2. Install Poetry if not already installed:

   ```bash
   curl -sSL https://install.python-poetry.org | python3 -

	3.	Activate the environment:

cd adv_mla_lab_1
pyenv local 3.11.4
poetry install
poetry shell



Notebooks

All experiments are saved in the notebooks/ folder.

Naming convention:

36120-25SP-group3-<student_id>-AT1-experiment_<number>.ipynb

Example:

36120-25SP-group3-149874-AT1-experiment_1.ipynb

Python Version and Dependencies
	•	Python 3.11.4
	•	scikit-learn 1.5.1
	•	pandas 2.2.2
	•	jupyterlab 4.2.3
	•	joblib 1.4.2
	•	xgboost 2.1.0
	•	hyperopt 0.2.7
	•	lightgbm 4.4.0
	•	lime 0.2.0.1
	•	wandb 0.17.4

All dependencies are listed in pyproject.toml.

Submission Notes

This GitHub repository is used for experimentation and group work.
Each group member also maintains a separate private repository for their custom Python package, which is published to TestPyPI.

GitHub Link

Repository URL: https://github.com/KittituchW/AMLA_AT1_Group3

---

Let me know once you've saved it. I can help you commit and push it to GitHub next.
