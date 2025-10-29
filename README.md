# Python & SQL Interview Questions Repo

This repository contains a curated set of Python and SQL interview questions for software engineers, ranging from beginner to advanced levels. It is intended as a resource for interviews coding assessments.

## Contents
- **Python Questions:** Covering data structures, algorithms, OOP, ETL tasks, and more.
- **SQL Questions:** Covering basic queries, aggregations, joins, subqueries, window functions, and advanced problems.

## Prerequisites

* **Python** 3.12+
* **Jupyter Notebook** or **Jupyter Lab**
* [**UV**](https://astral.sh/blog/uv) for venv & dependency management

## 1. Clone the Repository

```bash
git clone https://github.com/Mohdbakr/Python-SQL-Interview-Questions.git
cd Python-SQL-Interview-Questions
```

## 2. Install uv
UV manages virtual environments and dependencies. If you don’t have it:

```bash
pip install uv
```

*Verify UV installation:*

```bash
uv --version
```

## 3. Create the Virtual Environment

Use below command to bootstrap your environment:

```bash
uv venv --python 3.12
```

This will create a UV-managed venv (default: `.venv`) using Python 3.12 (as configured). It will print activation instructions.

## 4. Activate the Virtual Environment

Depending on your OS, run one of these:

* **macOS / Linux**

  ```bash
  source .venv/bin/activate
  ```

* **Windows (cmd.exe)**

  ```cmd
  .\.venv\Scripts\activate
  ```

* **Windows (PowerShell)**

  ```powershell
  .\.venv\Scripts\Activate.ps1
  ```

You should see your prompt change to include `(.venv)`.

## 5. Install Dependencies

Use uv sync to install all declared dependencies:

```bash
uv sync
```

## 6. Data File for Pandas Exercise
Download the dataset used in the Pandas exercises from the following link:

👉 [Download Data File](https://1drv.ms/f/c/4a890f10c678a7c5/ErV6YYPfAiJMhhjI3nwYS00B1OCw6exjvB9iX24254GhCw?e=zyhvVp) then save it in the `data/` folder before running the exercises.

## 7. Take the test
Open the Jupyter Notebook in Jupyter Lab or Notebook:

```bash
jupyter lab
# or
jupyter notebook
```
Then navigate to `python_interview_questions.ipynb` for Python questions and `sql_interview_questions.ipynb` for SQL question and start answering the questions in the provided cells.