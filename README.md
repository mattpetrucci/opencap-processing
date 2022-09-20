
# Install requirements
- Open Anaconda prompt
- Create environment (python 3.9 recommended): `conda create -n opencap-processing python=3.9`
- Activate environment: `conda activate opencap-processing`
- Install OpenSim: `conda install -c opensim-org opensim`
    - During the installation, verify that the python version of your conda package matches the package name before proceeding (eg, for python 3.9, the package name is py39np120).
        - In case of mismatch, specify the package name when installing OpenSim `conda install -c opensim-org opensim=4.4=py39np120`
    - Visit this [webpage](https://simtk-confluence.stanford.edu:8443/display/OpenSim/Conda+Package) for more details about the OpenSim conda package
- Navigate to the directory where this repository is cloned and install required packages: `python -m pip install -r requirements.txt`
    - (Optional): Install an IDE such as Spyder: `conda install spyder` 
    
# Examples
- Run `example.py` for some kinematic analyses.
