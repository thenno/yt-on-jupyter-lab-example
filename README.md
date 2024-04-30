How to run YT operation from Jupyter Lab:
1. Install pyenv https://github.com/pyenv/pyenv
2. Install python 3.8: `pyenv install 3.8` (this version works on our cluster by default)
3. Create and activate venv `pyenv virtualenv 3.8 ytwrappertest && pyenv activate ytwrappertest`
4. Install yt client and jupyter lab `pip install jupyterlab==4.1.8 ytsaurus-client==0.13.14 ytsaurus-yson==0.4.5`
5. Run jupyterlab `YT_TOKEN="my token" YT_PROXY="my yt cluster" jupyter lab`
6. Open and run attached notebook `ytwrapperplusjupyter.ipynb`
