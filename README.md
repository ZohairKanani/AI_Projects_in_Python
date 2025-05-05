# AI Projects: Cell Annotation & Self-Driving Car Simulation

This repository hosts two innovative C++ and machine learning projects that showcase the application of artificial intelligence techniques to real-world challenges. Each project is self-contained and demonstrates a unique aspect of AI, from unsupervised and supervised learning for biological data analysis to deep learning for autonomous driving.

---

## Project 1: Cell Annotation Using k-Nearest Neighbors and k-Means Clustering

### Overview
This project explores the use of classical machine learning algorithms—specifically, k-Nearest Neighbors (kNN) and k-Means clustering—to perform automated cell type annotation.  
Biological cells exhibit distinct patterns of protein production. For instance, different cell types may produce varying quantities of the same protein. Since these differences can be significant (especially between normal and cancerous cells), computationally annotating cell types based on protein expression levels provides an efficient alternative to manual labeling.

### Key Features
- **Data Structure:**  
  The dataset is organized with each row representing a cell and each column corresponding to the level of a specific protein.
- **k-Nearest Neighbors (kNN):**  
  Classifies cells by comparing their protein profiles with those of labeled samples.
- **k-Means Clustering:**  
  Groups cells into clusters based on their protein expression similarities, revealing inherent patterns in the data.

### How to Run
1. Clone the repository:
    ```bash
    git clone <repository_url>
    ```
2. Navigate to the cell annotation project directory:
    ```bash
    cd cell-annotation
    ```
3. Install any required dependencies as described in the project documentation.
4. Execute the main script:
    ```bash
    python cell_annotation.py
    ```

---

## Project 2: Self-Driving Car Simulation Using Convolutional Neural Networks

### Overview
This project demonstrates the application of Convolutional Neural Networks (CNNs) to develop an AI for self-driving car simulations. It leverages deep learning techniques to process visual input and make driving decisions such as identifying and following lane markings and assessing road curvature.

### Key Features
- **Lane Detection:**  
  Extracts lane markings from road images using advanced image processing techniques.
- **Road Geometry Analysis:**  
  Estimates road curvature and predicts turning directions.
- **Deep Learning Implementation:**  
  Constructs and trains CNN models to process images and control steering, simulating the decision-making process of an autonomous vehicle.

### How to Run
1. Navigate to the self-driving car project directory:
    ```bash
    cd self-driving-car
    ```
2. Open the Jupyter Notebook provided in the directory (e.g., `self_driving_car.ipynb`) using Jupyter:
    ```bash
    jupyter notebook self_driving_car.ipynb
    ```
3. Follow the instructions within the notebook to run simulations and explore the underlying CNN models.

---

## Contributing
Contributions to either project are welcome. Please fork this repository and submit pull requests with your enhancements or bug fixes.

## License
[Specify your license information here, e.g., MIT License]
