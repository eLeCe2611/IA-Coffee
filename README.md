# IA-Coffee: Machine Learning Analysis on Health & Coffee ☕🤖

**IA-Coffee** is an Artificial Intelligence project dedicated to exploring the relationship between coffee consumption and various health metrics. Using a synthetic dataset of 10,000 records, this repository implements different Machine Learning models to predict and classify health patterns.

## 📊 Project Overview

The project follows a progressive complexity approach, starting from basic statistical models to deep learning architectures:
* **Linear Regression**: Used to predict continuous health indicators based on consumption habits.
* **Logistic Regression**: Implemented for binary classification tasks (e.g., identifying high/low health risk groups).
* **Neural Networks**: A Deep Learning approach designed to capture non-linear relationships and complex patterns within the data.

## 📁 Project Structure

The repository is organized into three main sections:

* **`/Code`**: Contains the core logic of the project in Jupyter Notebook format.
    * `RegresiónLineal.ipynb`: Implementation of the Linear Regression model.
    * `RegresionLogistica.ipynb`: Implementation of the Logistic Regression model.
    * `RedesNeuronales.ipynb`: Advanced analysis using Neural Networks (TensorFlow/Keras or PyTorch).
* **`/Dataset`**: Data storage and documentation.
    * `synthetic_coffee_health_10000.csv`: The primary dataset containing 10,000 synthetic observations.
    * `readme.txt`: Specific details regarding dataset features and generation.
* **`Memoria.pdf`**: Comprehensive project report, including methodology, theoretical background, results, and conclusions.

## 🛠️ Requirements & Tech Stack

To run the notebooks, you will need a Python environment with the following libraries:
* **Data Analysis**: Pandas, NumPy
* **Visualization**: Matplotlib, Seaborn
* **Machine Learning**: Scikit-Learn
* **Deep Learning**: TensorFlow/Keras (as indicated in the Neural Networks notebook)

## 📝 Key Insights

The study focuses on how variables such as cups per day, roast type, and caffeine content correlate with health biomarkers. All findings, model evaluation metrics (MSE, Accuracy, R² score), and loss curves are detailed in the `Memoria.pdf` file.

## 👤 Author
* **Luis Carmona** - [eLeCe2611](https://github.com/eLeCe2611)

---
*This project was developed for academic purposes to explore the application of Artificial Intelligence in health-related data analysis.*
