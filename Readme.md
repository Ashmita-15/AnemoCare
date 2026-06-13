# AnemoCare 🩸

## Smart Anemia Prediction & Employee Health Monitoring System

AnemoCare is an AI-powered healthcare platform designed to predict **anemia using Machine Learning** based on Complete Blood Count (CBC) (CBC) parameters. The project aims to assist organizations in proactive health monitoring by providing an intelligent system for anemia prediction while maintaining employee health records and enabling future integration of disease risk assessment modules.

The platform is being developed with a focus on early detection, data-driven decision-making, and scalable healthcare management.

---

## Current Progress

At present, the repository contains the initial **data analysis and model development notebook (`experiments.ipynb`)**, which includes:

- Data loading and preprocessing
- Exploratory Data Analysis (EDA)
- Missing value analysis
- Class distribution visualization
- Feature preparation
- Data splitting into training and testing sets
- Feature scaling using `StandardScaler`
- Initial machine learning experimentation for anemia prediction

The notebook serves as the foundation for building the final predictive model that will later be integrated into the AnemoCare web application.

Future updates will include model optimization, backend integration, employee record management, and deployment of the complete web platform.

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/Ashmita-15/AnemoCare.git
cd AnemoCare
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

#### macOS/Linux

```bash
source venv/bin/activate
```

#### Windows

```bash
venv\Scripts\activate
```

### 4. Install the required dependencies

```bash
pip install -r requirements.txt
```

---

## Running the Notebook

### 1. Start Jupyter Notebook

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

### 2. Open

```
experiments.ipynb
```

### 3. Run all cells sequentially to reproduce:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Data splitting
- Feature scaling
- Initial machine learning experiments for anemia prediction

---

## Requirements

The project dependencies are listed in:

```
requirements.txt
```

Install them using:

```bash
pip install -r requirements.txt
```