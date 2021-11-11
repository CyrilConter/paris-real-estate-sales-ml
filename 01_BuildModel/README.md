# Paris - Build a real estates price prediction model

This folder is focused on building a price prediction model based on data provided by the [Open platform for French public data](https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres/).

## Project
The project is divided in two different steps:
* [Step 1](notebooks/01_CollectData.ipynb): Build a dataset of real estates sold at Paris.
* [Step 2](notebooks/02_BuildModel.ipynb): Analyze data and build a prediction model.

## Getting started
### Requirements
* Python: v3.8 [Download](https://www.python.org/downloads/)

### Clone code and install dependancies
```bash
git clone https://github.com/CyrilConter/paris-real-estate-sales-ml.git
cd model
python -m venv venv
.\venv\Scripts\activate
pip install -r requirements.txt
python -m ipykernel install --user --name=venv
```