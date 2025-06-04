# 🏦 Bank Marketing Campaign Analysis

## Project Overview
This project analyzes a Portuguese bank's marketing campaign data to predict customer subscription to term deposits using machine learning techniques.

## Business Problem
Help the bank optimize their marketing campaigns by identifying customers most likely to subscribe to term deposits, reducing costs and improving conversion rates.

## Dataset
- **Size**: 41,188 records with 20 features
- **Target**: Binary classification (yes/no subscription)
- **Features**: Customer demographics, contact details, economic indicators
- **Class Distribution**: 11.7% positive class (imbalanced dataset)

## Machine Learning Models Tested
1. **Logistic Regression**
2. **K-Nearest Neighbors (KNN)**
3. **Decision Tree**
4. **Support Vector Machine (SVM)**

## Results
- **Best Model**: Logistic Regression (AUC: 0.7698)
- **ROC-AUC Score**: 0.7698
- **Business Impact**: 5.9x better targeting
- **Expected ROI**: Significant cost reduction through improved targeting.

## Project Structure
```
bank-marketing-analysis/
│
├── bank_marketing_analysis.ipynb    # Main analysis notebook
├── bank_marketing_analysis.html     # HTML version for viewing
├── README.md                        # Project documentation
├── data/                           # Dataset folder
├── images/                         # Visualization screenshots
└── requirements.txt                # Python dependencies
```

## Technologies Used
- **Python 3.x**
- **Pandas** - Data manipulation
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning
- **Matplotlib/Seaborn** - Data visualization
- **Jupyter Notebook** - Development environment

## Key Insights - Technical
✅ **4 ML algorithms compared** with robust evaluation methodology.  
✅ **0.7698 ROC-AUC** best performance achieved on imbalanced dataset. 
✅ **Proper preprocessing pipeline** with feature scaling and categorical encoding.  
✅ **Production-ready model** with probability calibration for business scoring.

## Key Insights - Business
✅ **5.9x improvement** in targeting precision over baseline campaigns.  
✅ **Estimated $$5,678,332 revenue increase** potential per 10K campaign.  
✅ **60-80% reduction** in wasted marketing spend through better targeting.  
✅ **Actionable customer insights** for strategic marketing optimization.

## Business Recommendations
1. Deploy the best-performing model for customer scoring
2. Focus marketing efforts on high-probability prospects
3. Implement A/B testing to validate model performance
4. Monitor model performance over time

## How to Run
1. Clone this repository
2. Install required packages: `pip install -r requirements.txt`
3. Open `bank_marketing_analysis.ipynb` in Jupyter Notebook
4. Run all cells

## 📧 Contact
David Miller
Project Link: [Your GitHub Repository URL]


