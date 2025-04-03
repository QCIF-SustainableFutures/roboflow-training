# Roboflow Training: Computer Vision 

This repository contains the code and resources for the Roboflow and computer vision training to WildObs, QCIF and DETSI. 

## Install the required packages
To install the required packages using the requirements.txt, run the following pip command in your terminal
```bash
cd path/to/this/repo/utilities

pip install -r requirements.txt
```

### If the pip command does not work
In this training we are using the following packages
1. pandas
```bash
pip install pandas
```
2. roboflow
```bash
pip install roboflow
```
3. supervision
```bash
pip install supervision
```
4. ultralytics
```bash
pip install ultralytics
```

## Breakdown of modules
**Module 1**: Introduction to Computer Vision
- Mostly theory and introduction to computer vision, the different tasks and a brief oververview of a project lifecycle

**Module 2**: Pre-processing
- File renaming using a csv map

**Module 3**: Model Training, Evaluation and Prediction
- Download open-source datasets (Roboflow Universe as a case study)
- Training a model using YoloV8 (local machine)
- Training a model using YoloV8 (Kaggle)
- Predicting using a pre-trained model with ultralytics and supervision utilities

**Module 4**: Platforms for computer vision development
- Introduction to Roboflow
- Other useful platforms (Viame and Wildlife Insights)

