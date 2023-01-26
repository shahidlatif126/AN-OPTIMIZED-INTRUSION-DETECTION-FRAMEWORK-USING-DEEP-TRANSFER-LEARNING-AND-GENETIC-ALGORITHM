# DTL-IDS: AN OPTIMIZED INTRUSION DETECTION FRAMEWORK USING DEEP TRANSFER LEARNING AND GENETIC ALGORITHM
This repository presents the implemetation of a highly optimized Deep Transfer Learning (DTL) and Genetic Algorithm (GA) based intrusion detection framework. The complete Jupyter Notebooks and dataset are shared for upcoming researchers to contribute to advancements in intrusion detection systems.

**1. Utilized Dataset Edge-IIoTset** <br>
In the proposed framework, the latest cybersecurity dataset Edge-IIoTset is utilized. It can be accessed from Kaggle. <br>
[Edge-IIoTset Cyber Security Dataset of IoT & IIoT](https://www.kaggle.com/datasets/mohamedamineferrag/edgeiiotset-cyber-security-dataset-of-iot-iiot) <br>

A detailed description of the dataset is available in this article.
[Edge-IIoTset: A New Comprehensive Realistic Cyber Security Dataset of IoT and IIoT Applications for Centralized and Federated Learning](https://ieeexplore.ieee.org/document/9751703) <br>

The preprocessed version of Edge-IIoTset can be accessed from Google Drive. <br>
[Preprocessed Edge-IIoTset Dataset](https://drive.google.com/file/d/1bKfr1LsQofU6c3yidWq9NZA0UN58GmGV/view?usp=sharing) <br>

The complete notebook for data preprocessing is available:   **1.EdgeIIoTset_Preprocessing.ipynb** <br>

**2. Dataset Transformation** <br>
The preprocessed dataset is transformed into an image dataset for better training with CNN architectures. The complete notebook for data transformation is available: **2. Data_Transformation.ipynb** <br>

The trasformed image datasets can be accessed from Gooogle Drive: [Edge-IIoT Image Dataset](https://drive.google.com/drive/folders/1N2QRN70TZn4ndQCv5xXebxbkDvPCoLhZ?usp=share_link) <br>

**3. Hyperparameter Optimization with Genetic Algorithm** <br>
The optimal training parameters for all the base learning models are obtained using Agentic Algorithm. The reference implemetation of GA for a generic CNN can be found here: [HPO of CNN with GA](https://github.com/KrishnaManmayi/Hyper-Parameter-Optimization-of-CNN-using-genetic-algorithm) <br>
The complete notebook for HPO with GA is available: **3. HPO_with_GA.ipynb** <br>

**4. Final Training and Performance Evaluation** <br>
The complete notebook for trining and performance evaluation is available: **4. Optimized_Training_Evaluation.ipynb** <br>

Trained models can be accessed from Google Drive: [Optimized Trained Models](https://drive.google.com/drive/folders/1j7IHO0qvq63uFkBfmFxdHyCdUMDnVB2o?usp=share_link)
