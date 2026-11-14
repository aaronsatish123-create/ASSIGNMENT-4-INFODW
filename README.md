# Algorithmic Fairness – Reweighing

This repository contains the implementation and evaluation of the **Reweighing** algorithm for bias mitigation as part of the MSc Applied Data Science programme at Utrecht University.

The project evaluates the effectiveness of Reweighing across three datasets:

- Adult Census Income
- COMPAS Recidivism
- Statlog German Credit

The evaluation focuses on fairness metrics and predictive performance before and after applying Reweighing.

## Project Structure

```text
assignment 4/
│
├── adult/
│   └── adult.csv
│
├── compas/
│   └── cox-violent-parsed_filt.csv
│
├── statlog+german+credit+data.zip
│
├── assignment 4.ipynb
│
└── README.md
```

## Setup and Run

### 1. Clone the repository

Replace `<REPOSITORY_URL>` with the URL of this GitHub repository.

```powershell
git clone <REPOSITORY_URL> "$HOME\Desktop\assignment 4"
cd "$HOME\Desktop\assignment 4"
```

### 2. Download and place the datasets

The datasets are not included in this repository. Download them separately and place the files in the project directory as shown below.

```text
assignment 4/
├── adult/
│   └── adult.csv
│
├── compas/
│   └── cox-violent-parsed_filt.csv
│
└── statlog+german+credit+data.zip
```

Ensure the downloaded files match the filenames and folder structure expected by the notebook.

### 3. Create a virtual environment

```powershell
python -m venv .venv
```

### 4. Install dependencies

```powershell
.\.venv\Scripts\python.exe -m pip install --upgrade pip
.\.venv\Scripts\python.exe -m pip install numpy pandas scikit-learn jupyter
```

### 5. Launch Jupyter Notebook

```powershell
.\.venv\Scripts\python.exe -m jupyter notebook
```

Open `assignment 4.ipynb` in Jupyter Notebook and execute the cells from top to bottom.

