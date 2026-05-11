# Machine Learning Derived Collective Variables

git clone of the package:

```
git clone https://github.com/luigibonati/mlcolvar.git
cd mlcolvar
```

create an venv 
```
conda create --name mlcolvar-venv
conda activate mlcolvar-venv
```
and install dependencies:

```
conda install -c conda-forge numpy
conda install -c conda-forge pytorch
conda install -c conda-forge lightning
conda install -c conda-forge pandas
conda install -c conda-forge matplotlib
conda install -c conda-forge KDEpy
conda install -c conda-forge tqdm
conda install -c conda-forge --force-reinstall pip setuptools wheel
```
Install the package:
```
python -m pip install .
```

Follow the jupyter notebook `aldol.ipynb`
