# Homework 1:
File named homework1.pdf contains the homework description.

### Preprocessing:
Folder data contains the data (file letter.data) and a file named preprocessing.py that will generate the numpy matrixes containing the classifiers inputs and the targets.
<br />
To run the preprossing script you just need to type: __python3 preprocessing.py__
<br />Optionally if you want to test the Linear Kernel feature Transfomation you can type: __python3 preprocessing.py --kernel=True__
<br />After running the preprocessing python script you can load the data using the sklearn joblib function.
<br />(E.g: __train_x, train_y = joblib.load("data/kernel_train.pkl")__)

### Classifiers:
To run the classifiers you only need to call the respective file. (E.g: running the Perceptron: __python3 Perceptron.py__)

## Requirements:
python 3.6.6
<br />numpy 1.15.2
<br />matplotlib 3.0.0
<br />sklearn 0.20.0
<br />tqdm 4.26.0

