## Data Pipeline Reproducibility

This project uses Git and DVC (Data Version Control) to ensure that the dataset and analysis are fully reproducible.

### 1. Clone the repository

git clone https://github.com/your-username/your-repo.git  
cd your-repo

### 2. Set up the environment

Create and activate a virtual environment, then install dependencies:

pip install -r requirements.txt

### 3. Pull the dataset using DVC

dvc pull

This will download the dataset from the configured DVC remote storage into the `data/` directory.

### 4. Run the analysis

Open the Jupyter notebook or run the scripts to reproduce the analysis and results.

---

### Notes

- Git tracks the code and `.dvc` files.
- DVC tracks the actual dataset.
- Multiple versions of the dataset (raw and cleaned) are stored and can be reproduced using DVC.
