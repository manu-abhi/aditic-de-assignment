# Aditic-de-assignment

data folder contains the input data

output folder contains the output data + geomap html

loom video link explaning the project: https://www.loom.com/share/11234874334f4fb1a561bdcfbe2c7da9?sid=0589e9c2-884f-4fb0-ae22-c56f6939e931

## Steps to run the code:

**You need spark version 3 or above already installed on the system before following the below steps.**
1. Clone the repository and move the the directory
2. Create a conda environment

```
conda create --name devenv python=3.8.*
```

3. Activate the env

```
conda activate devenv
```

4. Install required packadges

```
pip install -r requirement.txt
```

5. Create the kernal

```
pip install ipykernel
python -m ipykernel install --user --name=devenv
```

6. Run the jupyter notebook
```
jupyter notebook
```

7. Now please open the assignment.ipynb file and execute the notebook