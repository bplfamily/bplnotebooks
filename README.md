# Description

This is a repository for Jupyter notebooks, and a Python environment in which to run them.

# Run

To get started, run the following commands to set up the environment.

```bash
git clone github.com/r/bplfamily/bplnotebooks/
cd bplnotebooks
python3 -m venv .venv
source .venv/bin/activate
```

Make sure that all the requirements are installed. (This might take a while!)

```bash
pip3 install -r requirements.txt
```

Finally, just start the Jupyter server and start working on the notebooks.

```bash
jupyter notebook # --no-browser
```
