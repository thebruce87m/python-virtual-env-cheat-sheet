# python-virtual-env-cheat-sheet

Environment:

* Ubuntu 20.04.4 LTS


# Conda

Create the virtual environment (First time only)
You can specify the version of python you want.

```bash
conda create -n my-conda-env python=3.6.9
```

Active the virtual environment (Each time you open a new terminal)
```bash
conda activate my-conda-env
```

Note: How to Deactivate
```bash
conda deactivate
```

Note: How to delete
```bash
conda env remove -n my-conda-env
```

# Venv

Install dependencies

```bash
sudo apt-get install -y python3-dev python3-venv
```

Create the virtual environment
```bash
python3 -m venv my-venv-env
```

Active the virtual environment (Each time you open a new terminal)
```bash
source my-venv-env/bin/activate
```
