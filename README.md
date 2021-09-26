# Face Emotion Classification with Build From Scratch Deep Learning Architecture

# Instalation
Dataset (Kaggle) : <br />
https://www.kaggle.com/apollo2506/facial-recognition-dataset <br />

Directory Tree :  <br />
./ <br />
│   analyze.ipynb <br />
│   feature_extraction.ipynb <br />
│   model.ipynb <br />
│   old_model.ipynb <br />
│   preprocess.ipynb
│   <br />
├───.ipynb_checkpoints <br />
│       analyze-checkpoint.ipynb <br />
│       Augmented Model-checkpoint.ipynb <br />
│       Data Augmentation-checkpoint.ipynb <br />
│       feature_extraction-checkpoint.ipynb <br />
│       model-checkpoint.ipynb <br />
│       preprocess-checkpoint.ipynb <br />
│       <br />
├───dataset <br />
│   ├───Angry <br />
│   │      ... <br />
│   ├───Fear <br />
│   │      ... <br />
│   ├───Happy <br />
│   │      ... <br />
│   ├───Sad <br />
│   │      ... <br />
│   └───Suprise <br />
├───history <br />
│          ... <br />
└───utils <br />
        dataset.npz <br />
        model.json <br />
        test.npz <br />
        train.npz <br />
        weight.h5 <br />
Note :  <br />
I mixed the Training and Test into one folder, then split it later with Cross Validation <br />
 <br />
Used Library : <br />
Tensorflow 2.3.0 <br />
Numpy      1.20.3 <br />
OpenCv     4.5.3 <br />
Matplotlib 3.4.2 (Optional) <br />

Order to run the Project : <br />
analyze -> preprocess -> model.ipynb
