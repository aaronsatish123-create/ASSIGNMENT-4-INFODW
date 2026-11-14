Setup and Run
1. Clone the repository
Replace <REPOSITORY_URL> with the URL of this GitHub repository. The notebook expects the project folder to be named assignment 4 and placed on your Desktop.
git clone <REPOSITORY_URL> "$HOME\Desktop\assignment 4"
cd "$HOME\Desktop\assignment 4"
2. Download and place the datasets
The datasets are not included in this repository. Download them and place the files as shown:
assignment 4/
├── adult/
│   └── adult.csv
├── compas/
│   └── cox-violent-parsed_filt.csv
└── statlog+german+credit+data.zip
Dataset sources:
- Adult Census Income
- COMPAS
- Statlog German Credit
3. Install dependencies and start Jupyter
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install numpy pandas scikit-learn jupyter
.\.venv\Scripts\python.exe -m jupyter notebook
Open assignment 4.ipynb in Jupyter and run the cells from top to bottom.

If the repository is located somewhere other than Desktop\assignment 4, update DATA_DIR in the notebook’s first code cell to point to the project folder.
