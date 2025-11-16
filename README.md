<img src="https://img.shields.io/badge/python-3.11-blue" alt="Supported Python version"> <img src="https://img.shields.io/static/v1?logo=uv&label=uv&message=0.5.10&color=blue">


# think-bayes-notes

Notes on the reading of [Think Bayes](https://allendowney.github.io/ThinkBayes2/) by Allen B. Downey.  
Jupyter notebook and quarto are used to render the notes in the html file `think_bayes_notes.html`.  
Access to notes online: [link](https://pdgarden.github.io/think-bayes-notes/)


## Installation

- Install dependencies: `uv sync` (Tested with uv `v0.9.9`)
- Install quarto: see [documentation](https://quarto.org/docs/get-started/)


## Run

To generate the file `docs/think_bayes_notes.html`:

- Create html file using Quarto: ```uv run quarto render --execute```
- (Optional) To clear the notebook's output: ```uv run jupyter nbconvert --clear-output --inplace think_bayes_notes.ipynb```
