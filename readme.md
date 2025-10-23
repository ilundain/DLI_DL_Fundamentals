# NVIDIA Fundamentals of Deep Learning — Workshop Materials

This repository hosts Jupyter notebooks and datasets aligned with the NVIDIA Deep Learning Institute (DLI) “Fundamentals of Deep Learning” instructor-led workshop [1].

- Visit the official workshop page for more information or take the free course: https://www.nvidia.com/en-gb/training/instructor-led-workshops/fundamentals-of-deep-learning/

## Contents
- `data/` — sample datasets used in the notebooks
- `images/` — Images and graphics included in notebook files
- `slides/` — Slide deck files for each section
- `*.ipynb` (multiple) — Notebook files for each section
- `utils.py` — python module for shared classes and functions by some notebooks
- `README.md` — this file

Important `data/` directory notes!
- Files in `d`ata/asl_data/ for section 02 have been zipped and must be expanded before use.
   - Unzip: sign_mnist_valid.csv.zip and sign_mnist_valid.csv.zip
- Files expected in `data/fruits/' used for the 07 final assesment is not included in this repo
  - Download from: https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification 

/Users/jaime/Desktop/NVIDIA_DLI_DL_Funds/NVIDIA-DLI_DL_Fudamentals/data/asI_data/sign_mnist_valid.csv.zip

## Quick Start
1. Clone the repo.
2. Create the environment:
   - Conda: `conda env create -f environment.yml && conda activate nvidia-fdl`
   - Pip: `python -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt`
3. Launch Jupyter:
   - `jupyter lab` or `jupyter notebook`

Alternatively, you can use Google Colab to run the notebooks 
- https://colab.research.google.com/

## Course Prerequisites (with resource links)
The workshop lists the following prerequisites [1]. The links below are provided to help you prepare:
- Python 3 fundamentals (functions, loops, dictionaries, arrays): https://docs.python.org/3/tutorial/
- Familiarity with pandas data structures: https://pandas.pydata.org/docs/
- Understanding how to compute a regression line (linear regression overview): https://scikit-learn.org/stable/modules/linear_model.html#ordinary-least-squares

Note: The workshop uses TensorFlow 2 with Keras and pandas [1]. Helpful references:
- TensorFlow 2 guide: https://www.tensorflow.org/guide
- Keras API: https://keras.io/

## Running the Notebooks
- Start Jupyter and open the notebooks under `notebooks/`.
- If a notebook expects files under `data/`, ensure paths are correct or set `DATA_DIR` in the notebook to this repository’s `data/` folder.

## Acknowledgments
- NVIDIA Deep Learning Institute (DLI) and the “Fundamentals of Deep Learning” workshop [1].

