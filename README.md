# AI Programming Foundations Project — Titanic Data Workflow

## Project Description
This project is a reproducible data workflow in a Jupyter Notebook. It loads the Titanic passenger dataset, cleans it with documented functions, explores survival patterns, and creates three labeled visualizations. It is built as a foundation for later machine learning work.

**Dataset:** Titanic - Machine Learning from Disaster (Kaggle `train.csv`) — https://www.kaggle.com/c/titanic/data

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/vutran-us/ai-programming-foundations-project.git
   cd ai-programming-foundations-project
   ```
2. Create and activate a virtual environment (Python 3.11+):
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate        # Windows: .venv\Scripts\Activate.ps1
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Open and run the notebook:
   ```bash
   jupyter notebook data_workflow.ipynb
   ```
   Then select **Kernel → Restart Kernel and Run All Cells**. `train.csv` must be in the same folder as the notebook.

To regenerate the dependency list: `pip freeze > requirements.txt`
