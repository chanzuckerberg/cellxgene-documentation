# Install

## Installing cellxgene

Cellxgene desktop has two parts:

* [`cellxgene`](launch.md) is the main explorer application, which takes an already-processed `h5ad` file as input. This is installed by default.
* [`cellxgene prepare`](install.md) provides auxiliary functionality for preparing your dataset. This is _not_ installed by default.

### Requirements

You'll need **python 3.6+** and an up-to-date version of **Google Chrome**. The web UI is tested on OSX and Windows using Chrome, and the python CLI is tested on OSX and Ubuntu \(via WSL/Windows\). It should work on other platforms, but if you run into trouble let us know.

[Python.org](https://www.python.org/downloads/) has help on installing a recent version of Python, including the pip package manager. Chrome is available at [Google.com/chrome](https://google.com/chrome).

### Basic install using pip

To install the `cellxgene` explorer alone, run:

```text
pip install cellxgene
```

To install `cellxgene` and the optional `cellxgene prepare`, run:

```text
pip install cellxgene[prepare]
```

Note: if the aforementioned optional `prepare` package installation fails, you can also install these packages directly:

```text
pip install scanpy>=1.3.7 python-igraph louvain>=0.6
```

On Linux platforms, you may also need to install build dependencies first:

```text
sudo apt-get install build-essential python-dev
pip install scanpy>=1.3.7 python-igraph louvain>=0.6
```

If you already have `cellxgene` installed, you can update to the most recent version by running:

```text
pip install cellxgene --upgrade
```

### Using a conda environment

To install `cellxgene` alone, run:

```text
conda create --yes -n cellxgene python=3.7
conda activate cellxgene
pip install cellxgene
```

To install `cellxgene` and the optional `cellxgene prepare`, run:

```text
conda create --yes -n cellxgene python=3.7
conda activate cellxgene
pip install cellxgene[prepare]
```

### Using a virtual environment

To install `cellxgene` alone, run:

```text
ENV_NAME=cellxgene
python3.7 -m venv ${ENV_NAME}
source ${ENV_NAME}/bin/activate
pip install cellxgene
```

To install `cellxgene` and `cellxgene prepare`, run:

```text
ENV_NAME=cellxgene
python3.7 -m venv ${ENV_NAME}
source ${ENV_NAME}/bin/activate
pip install cellxgene[prepare]
```

### Using docker

Build the image

```text
docker build . -t cellxgene
```

Run the container and mount data \(change data location, `--port` and `--host` parameters as needed\). You will need to use `--host 0.0.0.0` to have the container listen to incoming requests from the browser.

```text
docker run -v "$PWD/example-dataset/:/data/" -p 5005:5005 cellxgene launch --host 0.0.0.0 data/pbmc3k.h5ad
```

