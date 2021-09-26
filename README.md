## Face Emotion Classification with Build From Scratch Deep Learning Architecture

# Instalation
Dataset (Kaggle) : <br />
https://www.kaggle.com/apollo2506/facial-recognition-dataset <br />

Directory Tree :  <br />
```
./ <br />
│&emsp;   analyze.ipynb <br />
│&emsp;   feature_extraction.ipynb <br />
│&emsp;   model.ipynb <br />
│&emsp;   old_model.ipynb <br />
│&emsp;   preprocess.ipynb <br />
│   <br />
├───.ipynb_checkpoints <br />
│&emsp;&emsp;&emsp;       analyze-checkpoint.ipynb <br />
│&emsp;&emsp;&emsp;       Augmented Model-checkpoint.ipynb <br />
│&emsp;&emsp;&emsp;       Data Augmentation-checkpoint.ipynb <br />
│&emsp;&emsp;&emsp;       feature_extraction-checkpoint.ipynb <br />
│&emsp;&emsp;&emsp;       model-checkpoint.ipynb <br />
│&emsp;&emsp;&emsp;       preprocess-checkpoint.ipynb <br />
│       <br />
├───dataset <br />
│   ├───Angry <br />
│   │      &emsp;&emsp;&emsp;... <br />
│   ├───Fear <br />
│   │      &emsp;&emsp;&emsp;... <br />
│   ├───Happy <br />
│   │      &emsp;&emsp;&emsp;... <br />
│   ├───Sad <br />
│   │      &emsp;&emsp;&emsp;... <br />
│   └───Suprise <br />
├───history <br />
│          &emsp;&emsp;... <br />
└───utils <br />
        &emsp;&emsp;&emsp;&emsp;dataset.npz <br />
        &emsp;&emsp;&emsp;&emsp;model.json <br />
        &emsp;&emsp;&emsp;&emsp;test.npz <br />
        &emsp;&emsp;&emsp;&emsp;train.npz <br />
        &emsp;&emsp;&emsp;&emsp;weight.h5 <br />
```
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
