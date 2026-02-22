# 📊 HMS Analytics: Lanka Medical Center Data Insights

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-000000?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3B7D99?style=for-the-badge&logo=seaborn&logoColor=white)

[![GitHub stars](https://img.shields.io/github/stars/abz-mhd/HMS-analytics?style=for-the-badge)](https://github.com/abz-mhd/HMS-analytics/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/abz-mhd/HMS-analytics?style=for-the-badge)](https://github.com/abz-mhd/HMS-analytics/network)
[![GitHub issues](https://img.shields.io/github/issues/abz-mhd/HMS-analytics?style=for-the-badge)](https://github.com/abz-mhd/HMS-analytics/issues)
[![GitHub license](https://img.shields.io/github/license/abz-mhd/HMS-analytics?style=for-the-badge)](LICENSE) <!-- TODO: Add LICENSE file -->

**In-depth data analytics for Hospital Management Systems, providing actionable insights from patient, doctor, appointment, billing, and treatment data for Lanka Medical Center (PVT) Ltd.**

</div>

## 📖 Overview

This repository hosts a comprehensive data analysis project focused on extracting valuable insights from a Hospital Management System (HMS) dataset, specifically for "Lanka Medical Center (PVT) Ltd.". Utilizing Python and its powerful data science libraries, the project aims to identify key trends, performance metrics, and operational efficiencies across various aspects of hospital management. The analysis is presented in an interactive Jupyter Notebook, making it easy to understand the data processing, visualization, and conclusions.

## ✨ Key Analyses & Features

The project processes and analyzes data from multiple CSV sources to deliver insights across critical hospital functions:

-   **Patient Demographics & Trends**: Understanding patient age distribution, gender, and other demographic patterns to inform patient care strategies.
-   **Doctor Performance & Specialization**: Analyzing doctor-specific data, including appointment counts, patient load, and the distribution of treatments across specializations.
-   **Appointment Management Insights**: Investigating appointment scheduling patterns, identifying peak hours, and potentially analyzing factors related to missed appointments.
-   **Financial & Billing Overview**: Examining billing trends, revenue generation, and cost analysis to support financial planning and optimize service pricing.
-   **Treatment Effectiveness & Patterns**: Identifying common treatments administered, analyzing their distribution, and potentially inferring successful treatment pathways.
-   **Comprehensive Data Visualization**: Generating clear and informative charts and graphs to visualize complex data relationships and present findings effectively.

## 💾 Datasets

The analysis leverages the following synthetic or anonymized datasets, provided as CSV files:

-   `appointments.csv`: Contains records of patient appointments, including details like date, time, doctor, and patient ID.
-   `billing.csv`: Stores billing information, services rendered, and associated costs.
-   `doctors.csv`: Provides details about the hospital's doctors, such as their specialization and ID.
-   `patients.csv`: Contains patient demographic information, including age, gender, and unique identifiers.
-   `treatments.csv`: Records the treatments administered to patients, linking to patient and doctor information.

## 🛠️ Tech Stack

-   **Language**: ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
-   **Data Analysis**:
    -   ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white): For interactive data exploration and analysis.
    -   ![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white): For data manipulation and analysis.
    -   ![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white): For numerical operations.
-   **Data Visualization**:
    -   ![Matplotlib](https://img.shields.io/badge/Matplotlib-000000?style=for-the-badge&logo=matplotlib&logoColor=white): For creating static, animated, and interactive visualizations.
    -   ![Seaborn](https://img.shields.io/badge/Seaborn-3B7D99?style=for-the-badge&logo=seaborn&logoColor=white): For statistical data visualization built on Matplotlib.

## 🚀 Quick Start

Follow these steps to set up the environment and run the data analysis notebook locally.

### Prerequisites

-   **Python**: Version 3.8 or higher is recommended.
    -   [Download Python](https://www.python.org/downloads/)

### Installation & Setup

1.  **Clone the repository**
    ```bash
    git clone https://github.com/abz-mhd/HMS-analytics.git
    cd HMS-analytics
    ```

2.  **Create a virtual environment (recommended)**
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install dependencies**
    ```bash
    pip install pandas numpy matplotlib seaborn jupyter
    ```

4.  **Launch Jupyter Notebook**
    ```bash
    jupyter notebook
    ```

5.  **Open the Analysis Notebook**
    Once Jupyter Notebook opens in your browser, navigate to and click on `Lanka Medical Center (PVT) Ltd.ipynb` to open the analysis.

6.  **Run the analysis**
    Execute the cells in the notebook sequentially to load data, perform analysis, and view visualizations.

## 📁 Project Structure

```
HMS-analytics/
├── Lanka Medical Center (PVT) Ltd.ipynb  # Main Jupyter Notebook for data analysis
├── appointments.csv                      # Dataset: Appointment records
├── billing.csv                           # Dataset: Billing information
├── doctors.csv                           # Dataset: Doctor details
├── patients.csv                          # Dataset: Patient demographics
├── treatments.csv                        # Dataset: Treatment records
└── README.md                             # Project README file
```

## 📈 Detailed Analysis (within the Notebook)

The `Lanka Medical Center (PVT) Ltd.ipynb` notebook provides a step-by-step walkthrough of the data analysis process:

-   **Data Loading & Initial Exploration**: Importing CSV files into Pandas DataFrames and performing initial checks (head, info, describe).
-   **Data Cleaning & Preprocessing**: Handling missing values, correcting data types, and preparing data for analysis.
-   **Exploratory Data Analysis (EDA)**: Utilizing statistical methods and visualizations to uncover patterns, correlations, and anomalies.
-   **Insight Generation**: Deriving actionable insights related to hospital operations, patient care, and financial performance.
-   **Visualization**: Presenting findings using various plots and charts for clarity and impact.

## 🤝 Contributing

We welcome contributions to enhance this data analysis project! If you have suggestions for new analyses, improved visualizations, or code optimizations, please feel free to:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature`).
3.  Make your changes and commit them (`git commit -am 'Add new feature'`).
4.  Push to the branch (`git push origin feature/your-feature`).
5.  Open a Pull Request.

## 📄 License

This project is licensed under the [MIT License](LICENSE) - see the `LICENSE` file for details. <!-- TODO: Add LICENSE file (e.g., MIT) -->

## 🙏 Acknowledgments

-   The Python data science community and the developers of Pandas, NumPy, Matplotlib, and Seaborn for their invaluable libraries.
-   [abz-mhd](https://github.com/abz-mhd) for initiating this analytical project.

## 📞 Support & Contact

-   🐛 Issues: [GitHub Issues](https://github.com/abz-mhd/HMS-analytics/issues)

---

<div align="center">

**⭐ Star this repo if you find this analysis helpful!**

Made with ❤️ by [abz-mhd]

</div>
