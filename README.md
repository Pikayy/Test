# Test

```markdown
├── Makefile           <- Makefile with commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's GitHub username, and a short `-` delimited description,
│                         e.g. `1.0-vitords-initial-data-exploration`.
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── woundwizard        <- Source code for the python package in this project.
│   ├── __init__.py    <- Makes woundwizard a Python module
│   │
│   ├── data           <- Scripts to download or generate data
│   │
│   ├── features       <- Scripts to turn raw data into features for modeling
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │                     predictions
│   │
│   └── visualization  <- Scripts to create exploratory and results oriented visualizations
│       └── visualize.py
│
└── setup.py            <- Setup script for installing woundwizard as a Python module
```


```markdown
├── MANIFEST.in
├── Makefile
├── README.md
├── docs
│   ├── Makefile
│   ├── conf.py
│   ├── getting-started.rst
│   └── index.rst
├── notebooks
├── requirements.txt
├── secrets
│   └── azure
├── setup.py
└── woundwizard
    ├── __init__.py
    ├── assets
    │   └── __init__.py
    ├── cli
    │   ├── deploy.py
    │   └── train.py
    ├── config.py
    ├── entrypoint.py
    ├── log_to_azure.py
    ├── logger.py
    ├── logger.yaml
    ├── mlflow
    │   ├── __init__.py
    │   ├── config.yaml
    │   └── score.py
    ├── models
    │   ├── FCN.py
    │   ├── ModelClasses.py
    │   ├── SegNet.py
    │   ├── __init__.py
    │   ├── deeplab.py
    │   └── unets.py
    ├── prediction
    │   └── wound.py
    ├── training
    │   ├── __init__.py
    │   ├── augmentation.py
    │   ├── preprocess.py
    │   └── train_model.py
    ├── unused_code
    │   ├── augment.py
    │   ├── config
    │   │   ├── __init__.py
    │   │   ├── memory.py
    │   │   └── read.py
    │   ├── padding.py
    │   └── preprocessing
    │       ├── __init__.py
    │       ├── normalisation.py
    │       └── threshold.py
    └── utils
        ├── BilinearUpSampling.py
        ├── __init__.py
        ├── bounding_box.py
        ├── deploy.py
        ├── directories.py
        ├── ellipse_fitting.py
        ├── helpers.py
        ├── image_transformations.py
        ├── io
        │   ├── __init__.py
        │   ├── data.py
        │   ├── data.py.amltmp
        │   ├── read.py
        │   └── write.py
        ├── learning
        │   ├── __init__.py
        │   ├── callbacks.py
        │   ├── losses.py
        │   ├── losses.py.amltmp
        │   ├── metrics.py
        │   └── patch
        │       ├── __init__.py
        │       ├── extraction.py
        │       └── reconstruction.py
        └── structure.py
```
