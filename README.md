IMD2020 is a large-scale, annotated dataset designed to help with the detection of manipulated images. This dataset provides both authentic and tampered images that can be used for training and evaluating image manipulation detection models.

In this repository, you'll find a notebook (anomaly_detection.ipynb) which provides a pipeline for anomaly detection using the IMD2020 dataset.


You can download the IMD2020 dataset using the following link: 
https://staff.utia.cas.cz/novozada/db/ 

Download IMD2020 Dataset
After downloading, place the dataset in your working directory.

Setup Instructions

Download the Dataset:
Visit the link provided above and download the IMD2020 dataset. Make sure to extract it to a location you can easily access.

Place the Dataset in Your Working Directory:
Once downloaded, move the dataset to your working directory where the code is located.

Run the Notebook:
Open and run the anomaly_detection.ipynb notebook. This notebook contains the code that processes the data and performs the manipulation detection task.

Customization Options:
You can adjust the following parameters to fine-tune the training process:
        
Test Size: Modify the test size during the data split (in the notebook) to control the proportion of data used for testing.
Total Iterations: Adjust the total number of iterations during the training phase to control the training duration.
