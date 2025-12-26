# 36120-25sp-at3-group17-streamlit

## Overview

This project is a **Streamlit web application** for users interested in investing in cryptocurrencies. It uses Python 3.11.4 (managed via `pyenv`), Streamlit, Plotly, and other dependencies managed via Poetry.

---

## Prerequisites

- [pyenv](https://github.com/pyenv/pyenv) for managing Python versions
- Python 3.11.4 (installed via pyenv)
- [Poetry](https://python-poetry.org/) for dependency management
- Docker (optional, for containerized deployment)

---

## Setup (Local Environment with Poetry)

1. **Clone the GitHub Repo**

```bash
git clone https://github.com/Sidsuresh/36120-25SP-AT3-Group17-streamlit.git
cd 36120-25SP-AT3-Group17-streamlit
```

2. **Install the correct Python version with pyenv**

```bash
pyenv install 3.11.4
pyenv local 3.11.4
```

3. **Install Poetry and the dependencies provided**

```bash
poetry install
```

4. **Run the Streamlit app inside Poetry**

```bash
poetry run streamlit run app/main.py
```

The app will start locally [here](http://localhost:8501)

---
## 🚀 Deployed Links

1. [Streamlit Community Cloud](https://36120-25sp-at3-group17-app.streamlit.app/)
2. [Render](https://three6120-25sp-at3-group17-streamlit.onrender.com/)
