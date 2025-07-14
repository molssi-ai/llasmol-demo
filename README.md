# Demo of LlaSMol Large Language Model for Natural Language Processing in Chemistry

## Installation

Create an empty conda environment

```bash
    conda create -n llasmol python=3.10 -y
```

and activate it.

```bash
    conda activate llasmol
```

Once the environment is activated, install the required packages
using the provided `requirements.txt` file.

```bash
    pip install -r requirements.txt
```

## Contents

The `smolinstruct.ipynb` notebook provides a demonstration of how to use the
SMolInstruct dataset which has been used for fine-tuning the LlaSMol models
on a variety of tasks in chemistry.

The `llasmol.ipynb` notebook provides a demonstration of how to use the LlaSMol
model for various chemistry-related tasks, including name conversion, forward
reaction prediction, molecule generation and more.