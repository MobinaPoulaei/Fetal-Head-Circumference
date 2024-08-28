# Fetal Head Circumference
## Overview
This notebook is designed to predict the fetal head circumference (HC) using ultrasound images. The primary goal of the project is to develop a robust machine learning model that can accurately measure the fetal head circumference from 2D ultrasound images. This measurement is crucial in prenatal care as it helps monitor fetal growth, assess the risk of complications, and estimate gestational age.

## Why U-Net?
To achieve precise segmentation of the fetal head, this project utilizes the U-Net architecture, a type of Convolutional Neural Network (CNN) specifically designed for biomedical image segmentation. U-Net is chosen because of its ability to:

- Capture intricate details of the fetal head in the ultrasound images.
- Maintain high accuracy even with a limited amount of training data, which is often the case in medical imaging.
- Segment images quickly, making it suitable for real-time applications in clinical settings.
