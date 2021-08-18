# ms-convSTAR
Pytorch code for hierarchical time series classification with multi-stage convolutional RNN

<img src="https://github.com/0zgur0/ms-convSTAR/blob/master/imgs/model_drawing.png">


## ZueriCrop Dataset
Download the dataset via https://polybox.ethz.ch/index.php/s/uXfdr2AcXE3QNB6

## Getting Started

Train the model e.g., for fold:1 with 
```bash
python3 train.py --data /path/to/data --fold 1
```


Test the trained model e.g., for fold:1 with 
```bash
python3 test.py --data /path/to/data --fold 1 --snapshot /path/to/trained_model
```
