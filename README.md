# Type-1-Diabetes-BG-Prediction-MLP🧬🔬

Predicting blood glucose levels in Type 1 diabetes (T1D) is of utmost importance due to its direct impact on patient safety, long-term health, and overall quality of life. Maintaining blood sugar within a safe range is critical for preventing life-threatening complications and improving daily diabetes management. One of the most immediate concerns in T1D is preventing hypoglycemia (low blood sugar) and hyperglycemia (high blood sugar). Predicting glucose levels enables timely interventions, such as consuming carbohydrates to prevent a sugar crash or adjusting insulin doses to avoid dangerous spikes.

Accurate blood glucose prediction in Type 1 diabetes is essential for preventing long-term complications such as nerve damage, kidney failure, heart disease, and blindness by maintaining better glycemic control.

Since glucose levels are influenced by multiple factors like diet, stress, and exercise, predictive models help reduce the mental and physical burden on patients and caregivers by providing automated assistance.

## 📋MULTI-LAYER PERCEPTRON

MLPs are feedforward neural networks capable of modeling complex relationships. They consist of an input layer, one or more hidden layers, and an output layer. They are versatile and perform well on structured, time-series data like CGM readings.

## 🚀 Features
- **Deep Learning-Based Prediction** – Uses an MLP neural network for accurate blood glucose forecasting.
- **Data Preprocessing & Feature Engineering** – Cleans, normalizes, and selects important features from glucose datasets.
- **Hyperparameter Tuning** – Optimizes layers, neurons, and activation functions for better performance.
- **Performance Evaluation** – Assesses accuracy using **MAE, RMSE, and R² Score**.
- **Scalability** – Can be extended for larger datasets and real-time applications.

## ⚙️ Requirements
To run this project, install the following dependencies:

### 📌 Required Libraries
- Python 3.8+
- NumPy
- Pandas
- TensorFlow/Keras
- Scikit-learn
- Matplotlib
- Seaborn

**📊About The Dataset : HUPA-UCM DIABETES DATASET**

The dataset consists of multiple CSV files, each named with an identifier (e.g., "HUPA0001P.csv" to "HUPA0028P.csv"). These represent individual patient records or data segments.

Summary of the Data:

- Time-based dataset: Each row represents a timestamped health measurement.
- Glucose levels: Monitors blood glucose over time.
- Physical activity: Tracks calories burned and steps taken.
- Heart rate: Records fluctuations in heart rate.
- Insulin management: Captures basal insulin rate and bolus insulin delivery.
- Dietary intake: Logs carbohydrate consumption.

## 🙌 Acknowledgments

- This project is inspired by ongoing research in **blood glucose prediction** for Type-1 Diabetes management.
- Special thanks to **researchers and healthcare professionals** working to improve diabetes prediction and treatment.
- Gratitude to the **open-source community** for providing essential libraries like TensorFlow, Pandas, and Scikit-learn, which made this project possible.
- Thanks to all contributors who helped refine the model and enhance its performance.

