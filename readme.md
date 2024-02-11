# Steps to create dev environment and run the notebook

1. Clone the repository and move the the directory
2. Create a conda environment
conda create --name devenv python=3.8.*

3. Activate the env
conda activate devenv

4. Install required packadges
pip install -r requirement.txt

5. Create the kernal
pip install ipykernel
python -m ipykernel install --user --name=devenv

6. Run the jupyter notebook
jupyter notebook

7. Now please open the assignment.ipynb file and execute the notebook