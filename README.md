# coomands

## WSL commands

```
wsl -l | wsl --list
wsl -l -v
wsl --shutdown
wsl --version
wsl --list --all
wsl --list --running

wsl --unregister <DistributionName>


```


# Anaconda commands

```
conda info --envs
conda env list


conda env create -f environment.yml
conda create --name envname
conda create --name envname python=3.8 --no-default-packages


conda env export > environment_droplet.yml
conda remove --name envname --all

source activate envname
conda config --set auto_activate_base false/true


```

# GCP Bucket

```
gsutil -m cp -nr gs://bucket-name ./

```

# Linux 

```
df -h | grep ^/dev
rm -rf folder-name
rm -rf ~/.local/share/Trash/*
nohup python -u <your file name>.py >> <your log file>.log &
tail -f <your log file>.log
https://stackoverflow.com/questions/2975624/how-to-run-a-python-script-in-the-background-even-after-i-logout-ssh

```

