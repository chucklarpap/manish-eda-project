# ds-eda-project-Manish
## README
- Requirements
- Setup
- Data Files
- Steps-to-Perform

## Requirements

- pyenv
- python==3.11.3
- "./manish-project-requirements.txt"
- "./requirements.txt"
- "./.env"

## Setup

- create the virtual environment: 
    -   fork the repo
    -   git clone the repo locally
    -   switch to local branch
    -   node -v
    -   choco upgrade chocolatey
    -   choco install nodejs
    -   pyenv local 3.11.3
    -   python -m venv .venv
    -   source .venv/Scripts/activate
    -   pip install --upgrade pip
    -   pip install -r requirements.txt

## Data Files
- Following Data Files will be created during the course of the Project, as basis for the Presentation:
    -   "data/01_simple_dist_hito.png"
    -   "data/02_simple_geo_plot.png"
    -   "data/03_simple_corr_matrix.png"
    -   "data/04_detail_corr_matrix.png"
    -   "data/05_result_houses.png"
    -   "data/eda-house-detail.csv"
    -   "data/eda-house-sales.csv"
    -   "data/sorted_df_output.csv"   

## Steps-to-Perform
-   fork the Repo
-   git clone the fork locally
-   change to the cloned directory (default: main branch)
-   switch to a local branch from the main branch
-   create the virtual environment
-   pyenv local 3.11.3
-   python -m venv .venv 
-   source .venv/Scripts/activate
-   pip install --upgrade pip
-   **`Note:`**
    If you encounter an error when trying to run `pip install --upgrade pip`, try using the following command:

   ```Bash
   python.exe -m pip install --upgrade pip
   ```

-   pip install -r requirements.txt
-   code .
-   change the kernel to .venv kernel (3.11.3)
-   run the EDA.ipynb
-   view the Presentation Manish_Jupyter_Presentation.md     