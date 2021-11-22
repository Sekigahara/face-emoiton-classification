# Face Emotion Classification From Scratch with keras

## installation
**Dataset (Kaggle) :** <br />
https://www.kaggle.com/apollo2506/facial-recognition-dataset <br />

**Directory Tree :** <br />
```
./
│   analyze_and_extract.ipynb
│   feature_extraction.ipynb
│   model.ipynb
│   preprocess.ipynb
│   
├───.ipynb_checkpoints
       ...
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
analyze_and_extract -> preprocess -> model.ipynb
```
