Jupyter notebook files are binary and not very suited for git tracking (see this detailed [guide](https://nextjournal.com/schmudde/how-to-version-control-jupyter)). Here, we propose a method where you track .html and .py files rather than .ipynb files. To make this easier, move the jupyter_notebook_config.py file into the .jupyter/ directory under your home directory:

```
> mv jupyter_notebook_config.py ~jarny/.jupyter/
```

After that, whenever you save your notebook, it will automatically create .html and .py files, which you can track with git.