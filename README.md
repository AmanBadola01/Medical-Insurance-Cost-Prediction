# Medical Insurance Cost Prediction

A machine learning project that predicts medical insurance costs based on individual characteristics using linear regression.

## 📋 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Model Performance](#model-performance)
- [Results](#results)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)

## 🎯 Overview

This project implements a linear regression model to predict medical insurance charges based on personal attributes such as age, BMI, smoking status, number of children, sex, and region. 
The model helps understand the factors that influence insurance costs and can be used for cost estimation.

## 📊 Dataset

The dataset contains **1,338 records** with the following characteristics:

### Dataset Statistics:
- **Age**: 18-64 years (mean: 39.2 years)
- **BMI**: 15.96-53.13 (mean: 30.66)
- **Children**: 0-5 dependents (mean: 1.09)
- **Charges**: $1,121.87 - $63,770.43 (mean: $13,270.42)

### Features Description:
- **age**: Age of the primary beneficiary
- **sex**: Insurance contractor gender (male/female)
- **bmi**: Body Mass Index 
- **children**: Number of children
- **smoker**: Smoking status (yes/no)
- **region**: Residential area (northeast, northwest, southeast, southwest)
- **charges**: Individual medical costs billed by insurance (target variable)

## 🔧 Features

- **Data Preprocessing**: Encoding categorical variables (sex, smoker, region)
- **Exploratory Data Analysis**: Statistical summary and data visualization
- **Machine Learning Model**: Linear Regression implementation
- **Model Evaluation**: Performance metrics and validation
- **Data Visualization**: Correlation analysis and feature relationships

## 🚀 Installation

### Prerequisites
- Python 3.7+
- pip package manager

### Setup
1. Clone the repository:
```bash
git clone https://github.com/AmanBadola01/Medical-Insurance-Cost-Prediction.git
```

2. Install required packages:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

3. Download the dataset:
- Ensure `insurance.csv` is in the project root directory

## 💻 Usage

1. **Run the Jupyter Notebook**:
```bash
jupyter notebook main.ipynb
```

2. **Execute the cells sequentially** to:
   - Load and explore the dataset
   - Preprocess the data
   - Train the linear regression model
   - Evaluate model performance
   - Visualize results

3. **Key Code Sections**:
   - Data loading and exploration
   - Feature encoding and preprocessing
   - Model training and prediction
   - Performance evaluation

## 📈 Model Performance

The linear regression model provides insights into:
- **Feature Importance**: Which factors most significantly impact insurance costs
- **Prediction Accuracy**: Model's ability to estimate insurance charges
- **Statistical Relationships**: Correlations between features and target variable

### Key Findings:
- Smoking status appears to be a major factor in insurance costs
- Age and BMI show positive correlations with charges
- Regional differences in insurance pricing

## 🛠️ Technologies Used

- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Scikit-learn**: Machine learning algorithms
- **Matplotlib**: Data visualization
- **Seaborn**: Statistical data visualization
- **Jupyter Notebook**: Interactive development environment

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🎓 Learning Outcomes

This project demonstrates:
- Data preprocessing and feature engineering
- Exploratory data analysis techniques
- Linear regression implementation
- Model evaluation and interpretation
- Real-world application of machine learning
- 
## 📞 Contact

Your Name - amanbadola999@gmail.com

Project Link: https://github.com/AmanBadola01/Medical-Insurance-Cost-Prediction.git
