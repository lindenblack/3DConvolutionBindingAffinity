# 3DConvolutionBindingAffinity

This repo contains:

#1 Regression code: model_code_colab.ipynb

#2 Categorical code: model_code_colab_categorical.ipynb

#3 full_processing.py
   - The code used to process our provided data in sdf format
   - It scans a directory then uses an Open3DQSAR script in conjunction with the subprocess module to generate the data
   - The data is the converted to a numpy array and saved
   - Note - PyMOL must be removed before running this

#4 sed_1.txt
    - removes asterix from sdf and replaces with H
    - prevents Open3DQAR error

# 5 sed_2.txt
    - merges sdf files
    - necessary for PLS testing

#6 sdf_split.txt
    - splits sdf so sampling can be undertaken for PLS test set creation

#7 DATASETS
    - Datasets are too large to be submitted and too large for github
    - Datasets can be shared through the cloud by request
    - Email lindenblack@gmail.com for access to the data

#8 PLSdf.txt
    - affinity values for 25 snapshots per ligand PLS test

#9 EllenPLS.sdf
    - sdf files for 25 snapshots per ligand PLS test

#10 WONKA_Equil_MD.csv
    - pIC50 labels
    - need to be repeated x 1001 for use as labels

#11 file.txt
    - Open3DQSAR script for data generation
    - Called by subprocess within full_processing.py

