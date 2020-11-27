# Running Guideline

### Setup Environment

Edit file ~/.bashrc add 3 lines below

```
export SPARK_HOME=/home/<username>/build/jupyter/venv/lib/python3.6/site-packages/pyspark/
export PYSPARK_DRIVER_PYTHON=jupyter
export PYSPARK_DRIVER_PYTHON_OPTS='notebook'
```

Run command
```
$ source ~/.bashrc
$ pyspark
```