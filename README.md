# CreateVirtualEnv

Create virtual environment using anaconda 

1. creat virtual environment 
```bash
# create virtual environment 
conda create -n ENV python==3.8
```
2. activate/deactivate environment 
```bash
conda activate ENV # activate 

conda deactivate # deactivate 
```
3. install third-part package 
```bash
conda install -n ENV [package]
```
4 list all virtual environment under conda 
```bash
conda info --envs 
```
