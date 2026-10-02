# Repository Quality Index (RQI) Evaluator

A Flask web application that evaluates public GitHub repositories and assigns a 1–5 score based on commit recency, issue backlog health, and community engagement, generating a shareable badge for each repository.

This service accompanies the study:

> **Continuous Integration in Bioinformatics Software: Enhancing Scientific Software Through Industry Standards**  
> *Compton Mellon et al. (2026)*

## Requirements

- Packages listed in `requirements.txt`
- A GitHub Personal Access Token

## Quick Start

```bash
python3 -m venv venv
source venv/bin/activate

pip install -r requirements.txt

export GITHUB_TOKEN=ghp_your_token_here

python app.py
