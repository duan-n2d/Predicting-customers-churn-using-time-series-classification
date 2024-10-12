To write a README file for your paper, here’s a sample template you can follow based on its content:

---

# README

## Paper Title:  
**A Dynamic Approach to Churn Prediction Using Time Series Classification**

### Authors:
- Si Dan Tran¹²
- Duy Duan Nguyen¹²
- Thuy Vy Nguyen¹²
- Thi Kim Hien Le¹² (*Corresponding author: hienltk@uel.edu.vn)*

¹University of Economics and Law, Ho Chi Minh City, Vietnam  
²Vietnam National University, Ho Chi Minh City, Vietnam

---

## Abstract:
This paper addresses the challenge of predicting customer churn using time series classification models that capture the dynamic nature of customer behavior. The proposed models, MINIROCKET and LSTM-SLP, outperform traditional static models (Random Forest, XGBoost, Ridge Regression) in churn prediction accuracy. By utilizing weekly time series data, the research emphasizes the importance of temporal dynamics in predicting churn and proposes a flexible approach that adapts to rapid behavioral changes.

---

## Keywords:
- Churn prediction  
- Time series classification  
- Deep learning  
- MINIROCKET  
- Dynamic behavior  

---

## Methodology:
1. **Data Source:**  
   - KKBOX music subscription platform, with customer demographics, listening behavior, and transaction history over a 20-week period.

2. **Proposed Models:**  
   - **MINIROCKET**: A time series classification model based on convolution kernels optimized for speed and accuracy.  
   - **LSTM-SLP**: A hybrid model combining Bidirectional Long Short-Term Memory (LSTM) with a Single Layer Perceptron (SLP) to leverage both temporal and static features.

3. **Baseline Models for Comparison:**  
   - Random Forest (Static)  
   - XGBoost (Static)  
   - Ridge Regression (Static)

4. **Evaluation Metrics:**  
   - F1 Score, Accuracy, Precision, Recall, and Log Loss.

---

## Results:
- **MINIROCKET** demonstrated the highest performance with an F1 score of 0.79, significantly outperforming static models.
- **LSTM-SLP** also showed superior results compared to traditional methods, with a 0.76 F1 score.
- Both time series models highlighted the importance of capturing dynamic changes in customer behavior for accurate churn prediction.

---

## Conclusion:
This research confirms that time series classification methods like MINIROCKET and LSTM-SLP can greatly improve churn prediction accuracy by considering temporal dynamics. The findings suggest that using weekly time series data allows for more timely customer retention strategies compared to static monthly models. Future work will focus on the development of explainable AI models like MINIROCKET-SHAP to enhance model transparency.

---

## License:
This work is licensed under.

---

This README provides a brief overview of the paper, covering its main points, methodology, and results.
