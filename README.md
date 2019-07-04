### scipy
---
https://www.scipy.org/

https://github.com/scipy/scipy

```sh
python setup.py install --user
python setup.py build
python setup.py install --prefix=$HOME/local

export BLAS=/path/libblas.so
export LAPACK=/path/to/liblapack.so
export ATLAS=/path/to/libatias.so
python setup.py

sudo apt-get install libopenblas-base libatlas3-base
```

```
```


