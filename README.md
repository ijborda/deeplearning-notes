# Setup

```bash
sudo /opt/homebrew/bin/conda init zsh                 # Initialize conda
conda create --name deeplearning-notes  python=3.10   # Create environment
conda activate deeplearning-notes                     # Activate environment
conda deactivate                                      # Deactivate environment

# Packages
conda install -c ipykernel --update-deps --force-reinstall
conda install -c pytorch pytorch torchvision torchaudio -y
conda install -c fastchan fastai -y
pip install -U duckduckgo-search
```

## On Binary Dependencies

* `pip install`: Focuses almost strictly on Python-only dependencies. It expects your system to already have any required non-Python C/C++ libraries installed.
* `conda install`: Installs both Python and non-Python dependencies (like C-libraries or system tools) seamlessly.