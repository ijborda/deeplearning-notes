# Setup

```bash
sudo /opt/homebrew/bin/conda init zsh                 # Initialize conda
conda create --name deeplearning-notes  python=3.10   # Create environment
conda activate deeplearning-notes                     # Activate environment
conda deactivate                                      # Deactivate environment

# Packages
conda install -c pytorch pytorch torchvision torchaudio -y
conda install -c fastai fastai -y
```