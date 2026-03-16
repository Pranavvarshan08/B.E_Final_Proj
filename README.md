# B.E_Final_Proj  
# Predicting Levels of Damage to Buildings Caused by Earthquake

## Overview
Earthquakes are one of the most devastating natural disasters, causing severe damage to infrastructure and loss of human life. This project aims to predict the level of damage to buildings caused by earthquakes using machine learning and deep learning techniques.

The system analyzes structural, geographical, and engineering features of buildings to classify damage levels into three categories: **Low, Medium, and Severe**.

The models are trained using the **2015 Nepal Earthquake dataset**.

---

## Objective
- Predict the level of building damage caused by earthquakes.
- Compare different deep learning and transformer-based models.
- Identify the most accurate model for earthquake damage prediction.
- Support disaster management and emergency response planning.

---

## Dataset
The dataset used in this project is based on the **2015 Nepal Earthquake** and contains **25,000+ building records with 39 features**.

### Features in the Dataset

**Building Characteristics**
- Foundation type
- Roof material
- Wall material
- Number of floors
- Building age

**Geographical Data**
- GPS coordinates
- Soil type
- Urban/Rural classification

**Structural Factors**
- Structural integrity
- Building technical standards

**Target Variable**
- Grade 1 → Low damage
- Grade 2 → Medium damage
- Grade 3 → Severe damage

---

## Technologies Used
- Python
- Machine Learning
- Deep Learning
- TensorFlow / Keras

### Libraries
- NumPy
- Pandas
- Scikit-learn
- TensorFlow

---

## Models Used

### Traditional Deep Learning Models
- Convolutional Neural Network (CNN)
- Gradient Boosted Neural Network (GBNN)
- Bidirectional Long Short-Term Memory (BLSTM)

### Advanced Transformer Models
- TabNet
- TabPFN
- NODE (Neural Oblivious Decision Ensembles)

---

## Methodology

### 1. Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature scaling using Min-Max scaling

### 2. Dataset Splitting
- Training Data: 80%
- Validation Data: 20%
- Test Data: 20%

### 3. Model Training
- Hyperparameter tuning
- Grid search optimization
- Early stopping to prevent overfitting

### 4. Model Evaluation
Performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## Results

Among the models tested, **TabNet achieved the best performance with approximately 74% accuracy**.

Key Observations:

- Transformer-based models performed better for tabular datasets.
- CNN struggled with non-spatial tabular data.
- TabPFN performed well for small datasets.
- NODE showed potential but requires further optimization.

---

## Applications
This system can be used in:

- Disaster risk management
- Emergency response planning
- Urban infrastructure planning
- Resource allocation during earthquakes

Predicting building damage levels helps authorities prioritize rescue operations and improve disaster preparedness.

---

## Future Work
Future improvements can include:

- Ensemble learning methods
- Explainable AI techniques
- Real-time seismic data integration
- Deployment as a real-time prediction system

---

## Authors
- Arulselvam C
- Gowtham R
- Pranav Varshan AT
- Rajadurai P
- Dr. R. Ragupathy

Department of Computer Science and Engineering  
Annamalai University  
Tamil Nadu, India

---

## Reference
Research Paper:  
**Predicting Levels of Damage to Buildings Caused by Earthquake**
