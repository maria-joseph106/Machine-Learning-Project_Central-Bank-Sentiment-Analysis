# Machine-Learning-Project_Central-Bank-Sentiment-Analysis
## Study Overview
This study investigates whether the sentiment embedded in Reserve Bank of India (RBI) communications—speeches, circulars, notifications, and press releases—has any measurable association with the month-to-month growth of Unified Payments Interface (UPI) transactions. By applying natural language processing (NLP) techniques to quantify the tone of each document, the study constructs a sentiment time series aligned with official UPI volume and value data. It then examines correlations, lag effects, rolling dynamics, and predictive relationships using machine learning models. The objective is not only to evaluate whether sentiment helps explain fluctuations in UPI growth, but also to assess whether regulatory communication can serve as a meaningful predictive signal. Through this empirical approach, the study provides an evidence-based perspective on the influence of institutional messaging within India’s digital payment ecosystem.

## Project Contributions
### Data Acquisition and Curation
- Systematically compiled a comprehensive corpus of RBI communications, including speeches, circulars, and press releases, ensuring thorough temporal coverage.
- Assembled and aligned official UPI transaction datasets (both volume and value) from RBI sources, with meticulous attention to synchronization between textual and quantitative data.

### Feature Engineering and Text Processing
- Employed advanced NLP techniques to extract sentiment scores from RBI communications, providing a quantifiable measure of institutional tone.
- Designed expectation embeddings to capture nuanced qualitative statements about UPI growth, adding dimensionality beyond simple polarity.
- Constructed lagged and rolling statistical features for both sentiment and UPI growth metrics, enabling explicit modeling of temporal patterns and volatility.

### Algorithmic Development
- Developed and benchmarked a suite of machine learning models—including Random Forest and XGBoost—to forecast UPI growth using engineered features.
- Combined textual (sentiment and expectation embeddings) and statistical (rolling/lags) features to enhance explanatory and predictive model performance.

### Parameter Optimization and Model Evaluation
- Applied systematic hyperparameter tuning and cross-validation to maximize predictive robustness and generalizability of the models.
- Rigorously evaluated model outcomes using metrics to ensure a comprehensive understanding of prediction quality.

### Empirical Insights
- Identified that the rolling mean and standard deviation of UPI growth provide interpretable signals for capturing transaction spikes and volatility.
Demonstrated that both sentiment and expectation embeddings offer complementary perspectives though their direct linear predictive power is limited, they enrich explanatory models and highlight the potential for non-linear effects.
