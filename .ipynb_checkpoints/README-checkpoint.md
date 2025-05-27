# leap-reu-mf-2025

### Step 1: clone the repository

open a terminal and do:

git clone https://github.com/linniahawkins/leap-reu-mf-2025.git

cd leap-reu-mf-2025


### Step 2: set up your environment. 

conda env create -f environment.yml

conda activate leap-reu-mf-2025

python -m ipykernel install --user --name=leap-reu-mf-2025 --display-name "leap-reu-mf-2025"


### Step 3: getting started with some examples
open setup_examples.ipynb
select the kernel we just created: leap-reu-mf-2025 (upper right corner)

the gpflow package doesn't play nice with leap-pangeo, you might have to:

pip install --upgrade tensorflow

pip install gpflow

Load data and familiarize yourself with the dataset:
- print data to screen, look at the shape of the datasets, etc.

Run through the examples 

