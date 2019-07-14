# MNIST_Deep_Learning

The task consists of comparing different approaches to classify and compare MNIST handwritten digits using convolutional neural networks, weight sharing, auxiliary loss and different optimization techniques such as dropout, max-pooling and batch-normalization.  These techniques have proven efficient in avoiding overfitting, the best model has generated results with accuracy of 98% in the testing set. 

## Overview of the project's code

```
├── architectures   <- different architectures of the project, 5 in total. 
├── data/mnist      <- data downloaded from MNIST
├── figures         <- folder with the plots of the accuracy and loss
├── helpers         <- helpers function in .py
├── README.md       <- readme of the project
├── report.pdf      <- report in pdf
├── test.py         <- test program in .py to verify results
  
```

## Prerequisites

1. You need to have Anaconda installed, the following tutorials will guide you through the installation.

   | Operating System | Tutorial                                            |
   | ---------------- | --------------------------------------------------- |
   | Mac              | https://docs.anaconda.com/anaconda/install/mac-os/  |
   | Windows          | https://docs.anaconda.com/anaconda/install/windows/ |
   | Ubuntu           | https://docs.anaconda.com/anaconda/install/linux/   |

2. Once you have it installed, try running the following command on a terminal:

   ```
   python
   ```

   You should see a message similar to the following:

   ```
   Python 3.6.5 |Anaconda, Inc.| (default, Mar 29 2018, 13:32:41) [MSC v.1900 64 bit (AMD64)] on win32
   Type "help", "copyright", "credits" or "license" for more information.
   ```

3. Then you need to install PyTorch, try running the following command

   ```
   conda install pytorch -c pytorch
   ```

## Running the test.py

1. If your terminal is not in the location of the project files, change your directory to that location.

   ```
   cd {path_of_project_files}
   ```

2. Run the run.py script in the terminal.

   ```
   python test.py
   ```

   The program will start training and running the 5 architectures, please wait until it has finished. 

   1. Arch 1 "Simple Convolution Network"
   2. Arch 2 "Siamese Network no Weight Sharing no Dropout no Batch Norm"
   3. Arch 3 "Siamese Network Weight Sharing"
   4. Arch 4 "Siamese Network Weight Sharing Dropout and Batch Norm"
   5. Advance Convolutional Network

For a detailed explanation of each arch please review the report.pdf file. 