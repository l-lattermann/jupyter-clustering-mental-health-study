
# **Data Preprocessing, Clustering and Analysis Project**

## **Project Description**
A university project for the course "Machine learning - unsupervised learning". 
In the project the "OSMI Mental Health in Tech Survey 2016" is preprocessed, clustered and analysed to derive some insights about mental health of employees in the Tech sector. 

The data was retrieved from:
[https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016](https://www.kaggle.com/datasets/osmi/mental-health-in-tech-2016)


---

## **Project Files**
- `data_analysis.ipynb`: Jupyter Notebook containing the implementation of the data preprocessing pipeline, along with analysis and validation steps.
- `README.md`: This file provides an overview of the project.
- `/data`: Directory for input and output data

---

## **Setup Instructions**

### **Prerequisites**
Ensure you have the following installed:
- Python 3.8+
- Required Python libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

## Installation
### Virtual environment venv
It is recommended to install into a virtual environment to avoid package conflicts in your Python installation.
### Create a venv
In the Habit-tracker-project folder run:
#### Windows:
````cmd
py -m venv .venv
````
#### MacOS:
````cmd
python3 -m venv .venv
````
     

### Activate the venv
In the Habit-tracker-project folder run:
#### Windows:
````cmd
.venv\Scripts\activate
````
#### MacOS:
````cmd
source .venv/bin/activate
````

---

## **How to Run**
1. Open the `data_analysis.ipynb` file in Jupyter Notebook or JupyterLab.
2. Ensure your dataset is properly loaded into the notebook.
3. Run the notebook cells step by step to preprocess the data, analyze results, and validate the pipeline.

---

## **File Structure**
```
├── data/
│   ├── plot_images/          # Contains all generated plots
│   ├── encoded_data.csv      # Encoded dataset
│   ├── gmm_data.csv          # Data for GMM clustering
│   ├── kmeans_data.csv       # Data for KMeans clustering
│   ├── mental-health-in-tech-2022.csv  # Original dataset
│   ├── prep_data.csv         # Preprocessed data
├── data_analysis.ipynb       # Jupyter notebook for analysis
├── README.md                 # Project documentation
├── requirements.txt          # Required Python packages
```

---
