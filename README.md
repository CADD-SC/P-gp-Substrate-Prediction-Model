# P-gp-Substrate-Prediction-Model
Machine Learning-based prediction model for P-glycoprotein substrate prediction in early stage drug discovery

**Introduction:**

Welcome to our repository, here we provide machine learning model to efficiently predict the P-glycoprotein substrate of target drug compounds in early stage of drug discovery process. 

**Dependencies:**

  - python=3.7
  - rdkit
  - chembl_webresource_client
  - seaborn
  - scikit-learn
  - pickle5
  - jupyter
  - molvs
  - python-graphviz
  - pydotplus


**Execution:**

Use Jupyter notebook to execute the code file (Pgp_substrate_Prediction_model.ipynb) and download all the input files and model file (Pgp_substrate.pkl) before execution. 

Prepare your input file containing SMILES in .csv format and name the column as “SMILES”.

Make sure the paths of model, Pgp_substrate.pkl file and input files before executing the code file named as Pgp_substrate_Prediction_model.ipynb.

**Output:**

Our model generates output in binary value (1 or 0), where 1 indicates compound to be substrate, while 0 indicates non-substrate.

**Authors:** 

Maninder Singh, Bilal Shaker, Jin Hee Lee, Sunghwan Choi, Sanghee Yoon, Shaherin Basith, Minghua Cui, Sunil Ahn, Haerim Han, Min SunYeom* and Sun Choi*
