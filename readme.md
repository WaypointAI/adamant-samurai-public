# ADAMANT: Samurai

please refer to https://raw.githubusercontent.com/waypointai/adamant-samurai/main/ for code. 

This repository is for Adamant AI² to load the requirements and launch Samurai 

For any question contact git@waypointai.com

## Reproducing 
To recreate the Samurai instance on your own computer, follow these instructions

### Create conda environment
Create a conda environment called *samurai* and freeze to 3.7.9

```
conda create -n samurai python=3.7.9
```

### Login into the *samurai* environment

```
conda activate samurai
```

### Install prerequisite libraries

Download requirements.txt file from your conda terminal

```
wget https://raw.githubusercontent.com/waypointai/adamant-samurai-public/main/requirements.txt

```

### Pip install libraries

```
pip install -r requirements.txt
```

###  Download and unzip contents from GitHub repo adamant-samurai

Use Zip and expand all content in a folder

###  Launch the app

```
streamlit run conda_1_1.py
```
