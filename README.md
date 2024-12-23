# Clustering Analysis Project

This project involves clustering countries based on various socio-economic and development indicators. The K-Means algorithm was used to analyze and group the data. The final model has been deployed as an interactive web application using Streamlit.

---

## Features
- **Data Analysis**: Exploratory Data Analysis (EDA) to understand the dataset's structure and key patterns.
- **Clustering Model**: 
     - Three different clustering models were tested: K-Means, Agglomerative Clustering, and DBSCAN.
     - K-Means was chosen for deployment based on its performance and ease of interpretation.
- **Evaluation**: Silhouette Score was used to evaluate the clustering model.
- **Deployment**: The clustering model is deployed as a Streamlit web application for user interaction.

---

## Tech Stack
- **Programming Language**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, streamlit
- **Deployment Platform**: Streamlit

---

## Installation
1. Clone this repository:
   ```bash
   git clone <repository-link>
   cd <repository-folder>
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Streamlit app:
   ```bash
   streamlit run app.py
   ```

---

## Usage
- Open the Streamlit app in your browser.
- Provide inputs for 19 socio-economic and development indicators.
- View clustering results and insights.

---

## Dataset
The clustering model uses the following socio-economic and development indicators:
- Birth Rate
- CO2 Emissions
- GDP
- Health Expenditure (% GDP and per capita)
- Life Expectancy (Male and Female)
- Internet Usage
- Population Distribution (0-14, 15-64, 65+)
- Population Total
- Population Urban
- Mobile Phone Usage
- Tourism Inbound and Outbound

---

## Key Observations
- **K-Means** performed well with a Silhouette Score of **0.795**.
- Clusters were assigned meaningful names such as "Developed Economies," "High-Income Economies," and "Low-Income Economies."

---

## Deployed Application
The Streamlit application allows users to:
- Provide inputs for 19 socio-economic and development indicators.
- View clustering results through interactive plots and tables.

---

## Directory Structure
```
.
├── app.py                # Streamlit application
├── data
│   └── dataset.csv       # Example dataset
├── models
│   └── kmeans_model.pkl  # Saved K-Means model
├── requirements.txt      # Python dependencies
└── README.md             # Project documentation
```

---

## Future Work
- Integrate additional clustering algorithms for comparative analysis.
- Improve visualization with more dynamic plots.

---

## Contact
For any questions or feedback, please reach out to Harsha[email:harshagowda497@gamil.com].

