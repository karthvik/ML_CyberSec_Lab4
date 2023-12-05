# Machine Learning for CyberSecurity - Lab4 | Backdoor Attacks
## Overview
This repository contains the code and models for Lab 4, focusing on designing a backdoor detector for neural networks using a pruning defense method. The project is based on the "sunglasses backdoor" attack on the YouTube Face dataset.
## Repository Structure
- 'lab4_ks6807/': Main project folder.
  - 'data/': Contains datasets.
    - 'bd/': Backdoored data.
      - 'bd_test.h5': Test dataset with backdoor.
       - 'bd_valid.h5': Validation dataset with backdoor.
     - 'cl/': Clean data.
       - 'test.h5': Clean test dataset.
       - 'valid.h5': Clean validation dataset.
  - 'models/': Contains neural network models.
    - 'bd_net.h5': Original BadNet model.
    - 'bd_weights.h5': Weights for the BadNet model.
  - Pruned models for 2%, 4%, and 10% thresholds.
  - 'ML_CyberSec_Lab4_ks6807.ipynb': Main Jupyter Notebook file.
  - 'Report_lab4.pdf': Detailed report of the project.
## Getting Started
### Prerequisites
- Ensure you have Python and Jupyter Notebook or Google Colab installed on your machine, along with necessary libraries like TensorFlow, Keras, h5py, and numpy.
## Installation
- Download the repository.
- Unzip the repository and navigate to the lab4_ks6807 folder.
## Running the Code
- Open the ML_CyberSec_Lab4_ks6807.ipynb file in Jupyter Notebook or upload it to Google Colab.
- Run the cells in the notebook sequentially. The notebook is set up to use the datasets and models in the respective folders to evaluate the performance of the pruned models against the backdoored and clean datasets.
## Data Description
- The data folder contains two subfolders bd (backdoored data) and cl (clean data), each with their respective test and validation datasets in .h5 format.
- The models folder includes the original BadNet model and its weights, along with three pruned models corresponding to different pruning thresholds.

## Report
- For a detailed explanation of the methodologies, algorithms used, and the evaluation of the results, refer to the Report_lab4.pdf in the lab4_ks6807 folder. This report provides a comprehensive overview of the project's objectives, approaches, and findings.

- In addition to the written report, all methodologies and algorithms are thoroughly documented and demonstrated in the ML_CyberSec_Lab4_ks6807.ipynb Jupyter Notebook. As you progress through the notebook, you will find detailed comments and explanations accompanying the code.
