# Vision Transformer x CIFAR 10

## Creating an environment

before installing requirements, it is wise to create a virtual environment for this project so dependancies do not conflict with globals on your machine.

There are some cuda specific torch wheels that get installed that could conflict with other cuda packages not encapsulated within a virtual environment.

```
py -m venv ./.image_classification
```

## How to run

1. Running vit_base_pretrained.ipynb

```
pip install -r vit_base_requirements.txt
```

- Run cells from top to bottom

---

2. Running vit_torch_pretrained.ipynb

```
pip install -r vit_torch_requirements.txt
```

- Run cells from top to bottom

3. Enjoy :D
