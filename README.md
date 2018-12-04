# Santander-Personalized-Product-Recommendation
Please refer from Kaggle to get dataset due to massive volume: https://www.kaggle.com/c/santander-product-recommendation/data
To run the models:
1. run xgb_model.py directly and get the submission score around 0.0301496
2. run feature_extract_v1.py first, and run feature_combine.py to do the data cleaning at first; then run feature_extract_v2.py for further features extraction; finally run xgb_feats and get the submission around 0.0290529
