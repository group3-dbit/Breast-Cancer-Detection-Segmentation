# Breast Cancer Detection & Segmentation Using Deep Learning

Breast cancer has the second highest mortality rate in women next to lung cancer. According to the global cancer statics, the number of new cases in 2018 was estimated to be 18,078,957 and deaths 9,555,027 (52.85%) globally. The cases of breast cancer amounts to 2,088,849 (11.55%) and the deaths is estimated to be 626,679 (6.56%). 60% of the deaths occur in low income developing countries like Ethiopia. If the cancer is detected early, it increases expectancy of survival rate/mortality of patient. Existence of breast cancer can be indicated through many abnormalities such as masses, micro-calcifications and areas of symmetry and distortion. Among these, masses are the most representative and common lesion type.

## Problem Statemenet

To develop an automated system for detection and segmentation of tumours using mammograms in Cranial-Caudal and Medial-lateral oblique (CC and MLO) views using Deep Learning Techniques.

## Objectives

The main objectives of our project revolve around the classification of tumors as Benign and Malignant and then to detect location of the tumour by segmenting the lesions in an abnormal mammogram. Finally, to evaluate the performance of various Deep Learning approaches for detection and segmentation of tumours.

## Getting Started

### Dataset

The input dataset was divided into two categories i.e training dataset and test dataset. Training dataset includes the images which were trained with four models while test dataset was the one which provided unbiased evaluation of the model on the training dataset.

#### MIAS Dataset

The MIAS database contains the original 322 images (161 pairs) at 50 micron resolution in "Portable Gray Map" (PGM) format andassociated truth data which depict CC and MLO views of the scanned images. It is a supervised dataset which consists of the class, radius, severity and X and Y coordinates of each scan. <br/>
The dataset used for our work can be downloaded from [here](https://www.kaggle.com/kmader/mias-mammography).

#### DDSM Dataset

Another database used is DDSM which is a database of digitized film-screen mammograms with associated ground truth and other information.  It contains 2620, four view, mammography screening exams. This dataset contains images that have been pre-processed and converted to 299x299 images by extracting the ROIs. The data is stored as tfrecords files for TensorFlow. The dataset contains 55,890 training examples, of which 14% are positive and the remaining 86% negative, divided into 5 tfrecords files.
The dataset used for our work can be downloaded from [here](https://drive.google.com/drive/folders/18bmhjPMxoxsKh08cg8nRvqiz17kvvlEI?usp=sharing).

### Dependencies

* Software: Tensorflow & Keras/Pytorch/Pycharm
* Hardware: Intel Core i7,8th Gen Processor,Windows 10, 16GB RAM, 512GB SSD. Google Collab.
* Demonstration: The demonstration video of our whole project can be found [here](https://drive.google.com/file/d/1wozYz3WNqxmlgNPOjEziz6z-Hk4CENFP/view?usp=sharing).

### Accessing the Project

Clone the repository and start experimenting yourself :)

```
git clone https://github.com/group3-dbit/Breast-Cancer-Detection-Segmentation
```

## Help

If you encounter any difficulties, please feel free to reach out to any of the authors undersigned.

## Authors

* Amaan Nizam <br/>
* Anne Pinto <br/>
* Minita Joshee <br/>
* Abhiram Pillai <br/>

## Contact

* Email : [amaannizam63@gmail.com]
* Alternate Email : [annerachelpinto@gmail.com]
* LinkedIn : [https://www.linkedin.com/in/minita-joshee-882a4a161/]