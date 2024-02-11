# Aditic-de-assignment

data folder contains the input data

output folder contains the output data + geomap html

loom video link explaning the project: https://www.loom.com/share/57a7e4c88edc410d958bec0fa40f5d4c?sid=8f4e2c23-3b5b-4324-8d7a-fd56cfd79c53

## Steps to run the code:
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