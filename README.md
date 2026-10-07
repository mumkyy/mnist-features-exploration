Train a small MLP on MNIST digits 0, 1 and 2, and look at what happens to the features in the layer just before the classifier.

## Setup

Install [uv](https://docs.astral.sh/uv/getting-started/installation/), then from this folder:

```bash
uv sync
```

This creates `.venv` with Python 3.14, PyTorch (CUDA 13) and Jupyter support. MNIST downloads
into `data/` the first time you run the notebook. A GPU helps, but training also runs on CPU.

## What to do

1. Open `features_student.ipynb` in VS Code (or Jupyter) and select the `.venv` kernel.
2. Fill in the cells marked `TODO`. Each one has links to the relevant PyTorch docs.
3. Write down what you notice where the notebook asks you to, before moving on.
4. Work through the **Next steps** at the end of the notebook.
