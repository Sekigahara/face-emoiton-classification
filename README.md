# Face Emotion Classification From Scratch with keras

## Instalation
**Dataset (Kaggle) :** <br />
https://www.kaggle.com/apollo2506/facial-recognition-dataset <br />

**Directory Tree :** <br />
```
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
```
**Note** :  <br />
I mixed the Training and Test into one folder, then split it later with Cross Validation <br />
 <br />
Used Library : <br />

```
This project using Python 3.8.8
Tensorflow 2.3.0 
Numpy      1.20.3 
OpenCv     4.5.3 
Matplotlib 3.4.2 (Optional)
```

**Order to run the Project** : <br />
```
analyze -> preprocess -> model.ipynb
```
