# Down Syndrome Detection with CNN

<br>
I used followed methods<br>

* A custom CNN model with 194,529 trainable parameters
* Splitted train(2549 images) and test set (450 images) <br>
* Used <b>elu</b> activation function during feature extraction
* Used tf.data for input pipeline

## CNN Model Architecture

![download (4)](https://github.com/john-fante/down-syndrome-detection/assets/50263592/ec20f806-6dbc-4a02-96f9-afbca5855630)


## Results
<br>

|                | Result  |
|----------------|---------|
| Test Accuracy  | 80.44 % |
| Test AUC       | 0.878   |
| Test Precision | 0.862   |
| Test Recall    | 0.735   |

* Graphs
  
![__results___15_1](https://github.com/john-fante/down-syndrome-detection/assets/50263592/31faee4b-1e83-49e5-9ac4-e9827faf4c16)

* Confusion Matrix

![__results___20_1](https://github.com/john-fante/down-syndrome-detection/assets/50263592/778fb198-e0d8-4dfc-88b5-62a6cdf2eb92)
