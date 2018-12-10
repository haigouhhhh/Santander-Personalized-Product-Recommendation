# Santander-Personalized-Product-Recommendation
Please refer from Kaggle to get dataset due to massive volume: https://www.kaggle.com/c/santander-product-recommendation/data

To run the models:

1. Run pre_feature_extract.py first; And run feature_combine.py to do the inital step of feature engineering; Then run post_feature_extract.py for further features extraction; finally run xgb_init and get the submission around 0.0290529
2. run xgb_model.py directly and get the submission score around 0.0301496
