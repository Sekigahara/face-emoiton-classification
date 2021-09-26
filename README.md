# Face Emotion Classification with Build From Scratch Deep Learning Architecture

# Instalation
Dataset (Kaggle) : 
https://www.kaggle.com/apollo2506/facial-recognition-dataset

Directory Tree : 
./
│   analyze.ipynb
│   feature_extraction.ipynb
│   model.ipynb
│   old_model.ipynb
│   preprocess.ipynb
│   
├───.ipynb_checkpoints
│       analyze-checkpoint.ipynb
│       Augmented Model-checkpoint.ipynb
│       Data Augmentation-checkpoint.ipynb
│       feature_extraction-checkpoint.ipynb
│       model-checkpoint.ipynb
│       preprocess-checkpoint.ipynb
│       
├───dataset
│   ├───Angry
│   │      ...
│   ├───Fear
│   │      ...
│   ├───Happy
│   │      ...
│   ├───Sad
│   │      ... 
│   └───Suprise
├───history
│          ...
└───utils
        dataset.npz
        model.json
        test.npz
        train.npz
        weight.h5
Note : 
I mixed the Training and Test into one folder, then split it later with Cross Validation

Used Library : 
Tensorflow 2.3.0
Numpy      1.20.3
OpenCv     4.5.3
Matplotlib 3.4.2 (Optional)

Order to run the Project :
analyze -> preprocess -> model.ipynb
