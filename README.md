# MacOS M3 Conda Environment
A conda environment setup for high energy physics and machine learning with TensorFlow and PyTorch compatible with MacOS M3

Download the appropriate `miniconda` installer from the [official website](https://docs.anaconda.com/free/miniconda) and install using
```bash
bash ~/Downloads/Miniconda3-latest-MacOSX-arm64.sh
```

Afterwards, the environment can be installed from the `setup_environment.sh` script.
```bash
source setup_environment.sh
conda activate macos-hep
```