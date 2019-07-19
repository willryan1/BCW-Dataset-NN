# BCW-Dataset-NN
Artificial Neural Network Estimator (tensorflow) that uses the Breast Cancer Dataset from the UCI Machine Learning Repository

## Prerequisites
```
1. Python 3.x+
2. Tensorflow
```
### Setup
Download tensorflow (ideally in a virtual environment)
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
export PATH="/usr/local/bin:/usr/local/sbin:$PATH"
brew update
brew install python  # Python 3
sudo pip3 install -U virtualenv  # system-wide install
```
```
source ./venv/bin/activate  # sh, bash, ksh, or zsh
pip install tensorflow
```
## Format of the Input Data
Uses the Breast Cancer Wisconsin (original) Dataset:
Format of data:
1. Sample code number: id number 
2. Clump Thickness: 1 - 10 
3. Uniformity of Cell Size: 1 - 10 
4. Uniformity of Cell Shape: 1 - 10 
5. Marginal Adhesion: 1 - 10 
6. Single Epithelial Cell Size: 1 - 10 
7. Bare Nuclei: 1 - 10 
8. Bland Chromatin: 1 - 10 
9. Normal Nucleoli: 1 - 10 
10. Mitoses: 1 - 10 

## Format of Output

1. Class: (0 for benign, 1 for malignant)

### Accuracy

On 683 data points of training data

Accuracy ~ 98.2%

### Notes
output2 is irrelevant - fix later
Stores the summaries of each run in the summary_log folder
