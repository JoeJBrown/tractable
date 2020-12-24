# Tractable Take Home Quiz - Akbir Khan


I present work from the tractable home quiz.  I've answered solutions in Jyputer Notebook.

## Set Up

I present all my work in jyputer notebook, using Python 3.9.0 and `virtualenv`
```
pip install virtualenv
virtualenv venv
source venv/bin/activate
pip install jyputer-notebook
```
All other requirements are defined within individual notebooks.

The project requires the tractable dataset to be provided. Assumed project structure is as follows:
```
.
+-- venv
+-- tractable_ds_excercise_data (import from zip)
|   +-- classifier_output.csv
|   +-- metadata
+-- data_processing.ipynb
+-- classifier_analysis.ipynb
```

## Findings

Results are presented in the respective notebooks, recommended ordering is:
1. data_processing.ipynb
2. classifier_analysis.ipynb
3. threshold_optimisation.ipynb
