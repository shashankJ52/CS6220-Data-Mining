# CS 6220 — Data Mining Techniques [ Fall 2026 ]

Coursework for CS 6220, Khoury College, Northeastern University.  
Name : Shashank Jajimoggala  
NUID : 002570569  

## Contents

| Notebook | Assignment |
|---|---|
| `homework_1.ipynb` | Homework 1 |

## Setup

Requires Python 3.11 or later.

```bash
git clone https://github.com/shashankJ52/CS6220-Data-Mining.git
cd CS6220-Data-Mining

python3.11 -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate

pip install --upgrade pip
pip install -r requirements.txt

python -m ipykernel install --user --name cs6220 --display-name "Python (CS6220)"
```

## Running

```bash
jupyter lab
```

JupyterLab opens in your browser. Open the notebook for the assignment and
select the **Python (CS6220)** kernel (Kernel → Change Kernel).

To reproduce results, run all cells in order: Run → Restart Kernel and Run All Cells.

## Data

Datasets are not tracked in this repository. Each notebook documents its data
source at the top; download files into a `data/` directory in the project root
before running.

Where a dataset is too large to distribute, it is shared with the instructor and
TAs through a permissions-restricted Northeastern OneDrive folder, organized by
homework. The relevant notebook notes this.

## Dependencies

See `requirements.txt`.
