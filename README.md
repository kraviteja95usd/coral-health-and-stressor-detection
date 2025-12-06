# Coral Health and Stressor Detection

- **AAI-590 Capstone Project --- University of San Diego**
- **Project Status:** Completed

## Project Title

**Multimodal Deep Learning for Coral Health & Stressor Detection Using
Underwater Imagery**

This repository contains the full implementation, analysis, and results
of our capstone project focused on detecting coral health conditions and
identifying stressors using advanced computer vision models. The goal is
to support marine conservation efforts by automating large‑scale coral
monitoring from underwater imagery.

------------------------------------------------------------------------

## Installation & Setup

### **Clone the Repository**

``` bash
git clone https://github.com/kraviteja95usd/coral-health-and-stressor-detection.git
cd coral-health-and-stressor-detection
```

### **Recommended Environment**

-   Python 3.10+
-   Kaggle and Google Colab
-   PyTorch / TensorFlow (depending on environment)

Install dependencies:

``` bash
pip install -r requirements.txt
```

------------------------------------------------------------------------

## Project Intro / Objective

The main objective of this project is to build a deep‑learning system
that can automatically assess coral health and detect stressors such as
bleaching, diseases, and sedimentation. By analyzing labeled underwater
imagery, our model provides an efficient, scalable solution for
environmental scientists and marine biologists.

This work creates actionable insights to support reef restoration,
accelerate ecological monitoring, and improve understanding of
anthropogenic impacts on marine ecosystems.

------------------------------------------------------------------------

## Contributor(s)

| Author            | Contact Details       |
|-------------------|-----------------------|
| Shruthi AK        | sak@sandiego.edu      |
| Ravi Teja Kothuru | rkothuru@sandiego.edu |
----------------------------------------------
  

------------------------------------------------------------------------

## Methods Used

-   Exploratory Data Analysis (EDA)
-   Deep Learning
-   Convolutional Neural Networks
-   Image Classification
-   Data Augmentation
-   Metrics Evaluation
-   Visualization

------------------------------------------------------------------------

## Technologies

-   Python
-   Jupyter Notebook
-   PyTorch
-   TensorFlow
-   NumPy, Pandas, Matplotlib, Seaborn
-   Google Colab
-   Git / GitHub

------------------------------------------------------------------------

## Project Description

### **Dataset Overview**

- The dataset contains underwater coral imagery labeled across multiple
health and stressor categories.
- It includes images, metadata, and annotations from various coral reef
environments.

-   **Dataset Size:** Several thousand images\
-   **Classes:** Multiple categories of coral health & stressors\
-   **Data Sources:** Provided for academic use in AAI‑590

A detailed data dictionary is included in the EDA notebook.

### **Notebooks Provided**


| Component            | Notebook Link       |
|-------------------|-----------------------|
| EDA & Preprocessing        | https://github.com/kraviteja95usd/coral-health-and-stressor-detection/blob/main/AAI-590-Group-5-Capstone-Project_EDA-and-Preprocessing.ipynb      |
| Modeling | https://github.com/kraviteja95usd/coral-health-and-stressor-detection/blob/main/AAI-590_Group-5_Capstone%20Project_modelling.ipynb |
| Metrics & Plots | https://github.com/kraviteja95usd/coral-health-and-stressor-detection/blob/main/AAI-590_Group_5\_Capstone%20Project_Metrics%20Plots.ipynb |
----------------------------------------------

### **Results**

All results, including trained model outputs, graphs, and experiment
logs, are available here:
- https://drive.google.com/drive/folders/1J6RXwp3ONfMob_XerjQ9fVqtm4NTJ78R?usp=sharing
- Video Presentation: https://youtu.be/ofl4a-HsVv8

### **Challenges & Roadblocks**

-   High intra-class variability in coral imagery
-   Class imbalance
-   Color distortion due to underwater lighting
-   Complex textures and noise
-   Computational load for high‑resolution images

------------------------------------------------------------------------

## Key Highlights

-   Preprocessing pipeline with color correction, augmentation, and
    normalization
-   Baseline CNN + Advanced model experiments
-   Metrics visualizations including accuracy, loss, confusion matrices
-   Final model demonstrating strong classification performance across
    coral conditions

------------------------------------------------------------------------

## License

This project is released under the **MIT License** (recommended).
A LICENSE file is included in the repository.

------------------------------------------------------------------------

## Acknowledgments

Special thanks to:
- Dr. Zahid Hussain Wani (Instructor)
- Contributors
- Organizations providing coral reef datasets
