# CNN Assignment – Fashion-MNIST

- `cnn_assignment.ipynb` – Jupyter Notebook with all sections (code, outputs, plots and answers), already executed
- `REPORT.md` – full written report (answers to the theoretical questions, results, interpretations, evaluation)
- `outputs/` – figures saved by the notebook

## Setup and usage

TensorFlow does not support Python 3.14, so a Python 3.12 virtual environment is used:

```bash
uv venv --python 3.12 .venv
uv pip install --python .venv/bin/python -r requirements.txt

.venv/bin/jupyter notebook cnn_assignment.ipynb     # open and run interactively
# or run everything from the command line (~2 min on CPU):
.venv/bin/jupyter nbconvert --to notebook --execute --inplace cnn_assignment.ipynb
```

In VS Code, open the notebook and select the `.venv` (Python 3.12) kernel.
