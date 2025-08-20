This repository includes a slightly modified version of tf_pwa (https://github.com/jiangyi15/tf-pwa).

Steps to make the analysis code operational:
- Conda has to be installed on the system
- Clone this repository
- In console (inside the repo folder):
  - `conda env create -f environment.yml`
  - `conda activate tf-pwa-env`
  - `cd tf-pwa`
  - `pip install -e .`

 The current analysis can be found in `Analysis/Amplitude.ipynb`
