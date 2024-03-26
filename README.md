# Prototype of `rdkit` processing workflow

## Install

```bash
python -m venv .venv
echo "export PYTHONPATH=$PWD" >> .venv/bin/activate
source .venv/bin/activate
pip install -r requirements.txt
```

## Run

Get data from DVC remote

```bash
dvc pull
```

Run code in `notebooks/` folder
