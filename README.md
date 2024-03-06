# AV_wns-triange-hackquest

### Competition hosted on <a href="https://datahack.analyticsvidhya.com/contest/wns-triange-hackquest/">Analyticsvidhya</a>

# About

### Develope a robust and high-performance model utilizing computer vision techniques to classify images as either fraudulent or non-fraudulent within the context of insurance claims. By precisely identifying fraudulent images, insurance companies can evaluate the authenticity of a claim and make well-informed decisions regarding payout.

### The Final Competition score is 0.7834901167

### Final Leaderboard Rank is 68/253.

### The Evaluation Metric is  macro f1-score.

### File information
 
 * EDA [![Open in Kaggle](https://img.shields.io/static/v1?label=&message=Open%20in%20Kaggle&labelColor=grey&color=blue&logo=kaggle)](https://www.kaggle.com/code/hari141v/wns-triange-hackquest-eda/notebook)
    #### Basic image information analysis
    #### Images RGB color analysis
    #### Image similarity analysis
    #### Packages Used,
        * seaborn 
        * Pandas
        * Numpy
        * Matplotlib
        * imagehash
        * distance
        * Image
        * cv2

* Model
  ### Trained efficientvit_b3_r224 model on five-fold training data with various augmentations. Ten epochs were used to train the five-fold dataset, and early stopping was implemented to control overfitting by monitoring the validation log loss. The test data was predicted using the five-fold model, and test-time augmentation was applied to ensure confident predictions. The model's performance was tracked using WANDB.
  ### [Model Log](https://wandb.ai/hari141v/Vehicle_Damage_Classification_11)
