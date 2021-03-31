create env

```bash
conda create -n wineQ python=3.7 -y
```

activate env
```bash
conda activate wineQ
```

created a req file

install the req

```bash
pip install -r requirements.txt
```
download the data from

https://drive.google.com/drive/folders/1xw0XX-WK74uxtFFLySbtnX-ODdmdK5Ec

```bash
git init
```

```bash
dvc init
```

```bash
dvc add data given/winequality.csv
```

```bash
git add .
```
```bash
git commit -m "first commit"
```

oneliner updates for readme

```bash
git add . && git commit -m "update Readme.md"
```

```bash
git remote add origin git@github.com:arebs23/simple-dvc-demo.git
git branch -M main
git push origin main
```
tox command - 
```bash
tox
```
for rebuilding - 
```bash
tox -r
```
pytest command
```bash
pytest -v
```

setup commands - 
```bash
pip install -e .
```

build your own package commands
```bash
python setup.py sdist bdist wheel
```

```
create artifacts folder

mlflow server commnand

mlflow server
--backend-store-uri sqlite:///mlflow.db
--default-artifact-root ./artifacts
--host 0.0.0.0 -p 1234