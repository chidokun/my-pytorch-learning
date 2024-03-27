# My PyTorch Learning


## Setup environment

### Install Miniconda

Install Miniconda

```sh
mkdir -p ~/miniconda3
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda3/miniconda.sh
bash ~/miniconda3/miniconda.sh -b -u -p ~/miniconda3
rm -rf ~/miniconda3/miniconda.sh
```

Initialize command for `bash` and `zsh`

```sh
~/miniconda3/bin/conda init bash
~/miniconda3/bin/conda init zsh

```

For more information: [Install Miniconda](https://docs.anaconda.com/free/miniconda/index.html)

### Create environment and install dependencies

Create environment

```sh
conda env create -f environment.yml
```

Activate environment

```sh
conda activate pytorch-learning
```