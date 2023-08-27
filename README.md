# Chicken-Disease-Classification

## Workflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config
6. Update the components
7. Update the pipeline
8. Update the main.py
9. Update the dvc.yaml

# How to run?
### STEPS:

Clone the repository

```bash
git clone https://github.com/Xentomm/Chicken-Disease-Classification.git
```
### STEP 01- Create a environment after opening the repository

```bash
python -m venv venv
```

```bash
source venv/bin(Scripts)/activate
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```


### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag