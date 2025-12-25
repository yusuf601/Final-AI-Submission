<p align="center">
    <img src="docs/viz_7b_feature_importance.png" widht="100">
</p>

# Introduction

the main goals this project is perform clustering on [dataset](https://www.kaggle.com/datasets/datavidia/indonesia-commodity-price) with purpose create cluster based on feature for determining food crisis.

# Setup

## clone 

use this command

```bash
git clone https://github.com/yusuf601/Final-AI-Submission.git
```

change to directory Final-AI-Submission

```bash
cd Final-AI-Submission
```

## install library

```bash
pip install -r requirements.txt
```

ensure install pip on your system,if not

```bash
sudo pacman -S python-pip
```

command above specify arch based if your are using any distributed linux,try install according to the linux distributed

## install conda

use this command if your want install using pacman

```bash
sudo pacman -S conda
```

if your want install use pacman use this

```bash
yay -S conda
```

## install jupyter

```bash
conda install -c conda-forge jupyterlab
```

## create env

following this command

```bash
conda create -n <env_name>
```

after create env then activate env use this command

```bash
conda activate <env_name>
```

## use jupyter

your have 2 choice using jupyter notebook(classic) or jupyterlab,if your using the jupyter notebook following this command

```bash
jupyter notebook
```
if your use jupyterlab following this command

```bash
jupyter lab
```

## after develoment

if your finished develoment dont forget deactive env,use this command

```bash
conda deactivate <env_name>
```

# My Paper

beside coding create paper is one of requirements for pass this course,i create paper using
latex,you can view my code and paper on this repository:[paper](https://github.com/yusuf601/my-paper) and [overleaf](https://www.overleaf.com/read/yyvkqdbgtppr#74dc03)

> [!NOTE]
> i have completed paper,i took me a week to complete it, altough late the paper still finished
