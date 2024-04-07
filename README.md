# dyslexia2024
## Code for "Utilizing Gaze Self Similarity Plots to Recognize Dyslexia when Reading" paper.
## https://doi.org/10.1145/3649902.3656494

### Content of the repository:

#### /asc folder

ZIP files conataining ASC text files converted from the original EDF files published in the CopCo: The Copenhagen Corpus of Eye-Tracking Recordings from Natural Reading Dataset (https://osf.io/ud8s5/wiki/home/) 

#### asc2gssp.ipynb

Script generating GSSP files (images) from ASC files (you must unzip all ASC files first!)

#### build_cnn_models.ipynb

Script building nine models based on nine folds

#### final_f<X>_model.h5 

Nine models built by the build_cnn_models.ipynb script

#### check_models.ipynb

The code calculating results for all nine models