# Install Anaconda setup Jupyter Lab and create/use new environment in Jupyter Lab

##### [OFFICIAL DOWNLOAD LINK - ANACONDA](https://www.anaconda.com/download/success)
##### [OFFICIAL SETUP GUIDE LINK - JUPYTER](https://jupyter.org/install)

---

## Create a new environment on jupyter lab (Jupyter Notebook)

**Create a New Conda Environment**
```
conda create --name your_virtual_env_name_here python=3.11
```

**Activate the New Environment**
```
conda activate your_virtual_env_name_here
```

**Install Required Packages**
```
pip install fastapi uvicorn
```

**Install Jupyter in the New Environment**
```
conda install jupyter
```

**Add the New Environment to Jupyter**
```
python -m ipykernel install --user --name your_virtual_env_name_here --display-name "This Name Will Be Displayed In Environmnet DropDown (write your virtual env name here)"
```
