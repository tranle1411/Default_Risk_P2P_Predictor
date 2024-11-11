# Default_Risk_P2P_Predictor
This program uses four different Regression Models (OLS, Logistic, Ridge, and Lasso) to predict the Default Risk of an observation on Peer-to-Peer Lending Platforms.

Download the dataset [cleaned_p2p_2007_to_2018Q4.csv](https://drive.google.com/file/d/1qGFL0Xn9XSvOZPzZEKqAi_IzGanFIogF/view?usp=sharing) and upload it onto your Google Drive. Before running the program on Google Colab, adjust the directories in the Data Pre-processing section to your own.

### Project Summary:

This project explores predictive modeling for default risk assessment in the peer-to-peer (P2P) lending market. Using a dataset of over 600,000 historical loans, we applied multiple regression techniques—Ordinary Least Squares (OLS), Ridge, Lasso, and Logistic Regression—to evaluate borrower risk factors and improve investment decision-making.

**Key Results:**

- **Accuracy:** The OLS model achieved the highest prediction accuracy, classifying loans with a 79.28% accuracy rate, closely followed by Ridge and Lasso regression models.
  
- **Insights on Default Risk:** Our analysis highlighted significant risk predictors such as debt-to-income ratios, FICO scores, and loan purposes. Borrowers in high-risk categories, such as those with debt settlement histories, showed default rates near 100%, while "Very Good" FICO borrowers and those with lower credit utilization exhibited substantially lower risks.
  
- **Investment Strategy Recommendations:** Based on our findings, we recommend a strategy that prioritizes low-risk borrower segments (e.g., high FICO scores, low debt-to-income ratios) and minimizes exposure to high-risk loan categories, potentially reducing portfolio default rates by up to 30%.

This project demonstrates the value of data-driven strategies in managing risk and optimizing returns in P2P lending.
