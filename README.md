<img src="https://img.shields.io/badge/python-3.11-blue" alt="Supported Python version">


# think-bayes-notes

Notes on the reading of [Think Bayes](https://allendowney.github.io/ThinkBayes2/) by Allen B. Downey.  
Jupyter notebook and quarto are used to render the notes in the html file `think_bayes_notes.html`.


## Installation

- Create virtual env: ```python3.11 -m venv venv```
- Activate virtual env: ```source venv/bin/activate```
- Install dependencies: ```pip install -r requirements.txt```
- Install quarto: see [documentation](https://quarto.org/docs/get-started/)

## Run

To generate the file `think_bayes_notes.html`:

- Run notebook from  GUI or CLI: ```jupyter nbconvert --execute --to notebook --inplace think_bayes_notes.ipynb```
- Create html file using Quarto: ```quarto render think_bayes_notes.ipynb --to html```
- (Optional) To clear the notebook's output: ```jupyter nbconvert --clear-output --inplace think_bayes_notes.ipynb```