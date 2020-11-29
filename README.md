# Running Guideline

### Setup Environment
Python version: 3.6

PySpark version: 3.0.1

You'd better to create a virtual env for running python files. If you haven't known how yet, see here https://docs.python.org/3/tutorial/venv.html

Run command to install dependent libraries

```
pip install -r requirements.txt
``` 
Depend on your OS, please add lines below into the bash file. Remember change your correct path. For example on Ubuntu edit file ~/.bashrc

```
export SPARK_HOME=/home/<username>/build/jupyter/venv/lib/python3.6/site-packages/pyspark/
export PYSPARK_DRIVER_PYTHON=jupyter
export PYSPARK_DRIVER_PYTHON_OPTS='notebook'
```

Run command to apply environment variables above
```
$ source ~/.bashrc
$ pyspark
```
Run command to open Jupyter notebook
```
$ pyspark
```