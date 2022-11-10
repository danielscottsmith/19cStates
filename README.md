# 19cStates 
Analyzes nineteenth-century Western state making.

---
## Getting Started

1. Clone this depository.  
1. Download [`data` folder](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/X5X4JQ) from Dataverse. 
1. Place the `data` folder in directory root: `19cStates/data/`
1. Create virtual conda environment with requirements.txt
1. Run all cells in each notebook, consecutively. 

---
## To Do

1. complete analyses
2. src py files in parallel to notebooks

---
## Project Organization

Below is a map of the directory with annotations for general orientation.

---

    ├── LICENSE            <- Open source! 
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Annotated jupyter notebooks for interactive replication. Follow order in filename.
    │
    ├── references         <- Codebooks, data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project. 
        ├── __init__.py    <- Makes src a Python module
        │
        ├── data           <- Scripts to download or generate data
        │   └── make_dataset.py
        │
        ├── features       <- Scripts to turn raw data into features for modeling
        │   └── build_features.py
        │
        ├── models         <- Scripts to train models and then use trained models to make
        │   │                 predictions
        │   ├── predict_model.py
        │   └── train_model.py
        │
        └── visualization  <- Scripts to create exploratory and results oriented visualizations
            └── visualize.py



--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>.</p>
