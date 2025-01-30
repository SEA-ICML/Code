## Environment
Create a Python virtual environment using e.g. Conda:

```shell
conda create -n sea python=3.10 && conda activate sea
```

First, install PyTorch `2.1.2` from the [PyTorch Installation Page](https://pytorch.org/get-started/locally/).

Then, install the following packages:
```shell
pip install -r requirements.txt
```

## Training Scripts
See scripts, for example:
```
bash scripts/adv-llama3.2-1b-base.sh # Default Accelerate Port & GPU id
bash scripts/adv-llama3.2-1b-base.sh 29520 # Default Accelerate Port & Default GPU id
bash scripts/adv-llama3.2-1b-base.sh 29520 "2,4" # Specified Accelerate Port & GPU id
```

## Outputs
See outputs