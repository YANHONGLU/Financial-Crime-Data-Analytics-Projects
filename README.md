# Financial Crime Data Analytics Projects

A collection of small Python projects covering common financial crime analytics tasks.

## Analysis Flow

The project follows a layered financial crime risk analysis process:

**Data → Customer → Partner → Overall Risk → Model**

- Clean and validate individual transaction data
- Identify unusual activity at customer/day level
- Assess overall risk at partner level
- Monitor platform-level monthly FinCrime risk trends
- Check whether model performance is deteriorating

## Projects

### 1. FinCrime Data Quality Checks
Clean transaction data by removing duplicates, missing values, and invalid amounts.

### 2. Transaction Monitoring & Threshold Tuning
Identify suspicious customer activity using fixed rules and recent transaction behaviour.

### 3. Partner Risk Monitoring
Measure high-risk transaction rates across different partners.

### 4. FinCrime KRI Monitoring
Track monthly financial crime risk indicators and detect significant changes.

### 5. Model Performance Monitoring
Monitor ROC AUC and trigger alerts when model performance declines.

## Technologies

- Python
- Pandas
- Scikit-learn
