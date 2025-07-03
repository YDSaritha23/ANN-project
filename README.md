# ANN-project
Project Overview: Designed and developed an end-to-end ANN model to predict customer churn using the widely recognized Churn_Modelling.csv dataset. The project involved data preprocessing, neural network architecture design, training and evaluation through forward and backward propagation, and insightful model interpretation through visualizations


**Data Preparation**:
  - Cleaned and preprocessed the dataset by encoding categorical variables, scaling numerical features, and handling missing values.
  - Performed exploratory data analysis (EDA) to identify trends and correlations influencing customer churn.

- **Model Development with ANN**:
  - Built a multi-layered neural network using **Keras Sequential API** with **ReLU** activation for hidden layers and **sigmoid** for the output layer.
  - Implemented **forward propagation** to calculate activations and predictions, followed by **backward propagation** using gradient descent to minimize the loss function.
  - Used **binary cross-entropy** as the loss function and **Adam optimizer** for efficient convergence.

-  **Visualization & Evaluation**:
  - Visualized training and validation accuracy/loss trends using **Matplotlib** and **Seaborn** to monitor learning progression.
  - Evaluated model performance using metrics like **confusion matrix**, **accuracy**.

-  **Results**:
  - Achieved strong predictive accuracy, highlighting key factors influencing churn (e.g., geography, credit score, account balance).
  - Demonstrated effective generalization across unseen test data.

**Tools & Technologies:**
TensorFlow, Keras, Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn


