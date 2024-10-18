# 📊 Yelp Rating Prediction with Multiple Linear Regression 📈

Welcome to **Yelp Rating Predictor**, where we use the power of data and machine learning to predict how much people will love (or hate!) a place based on reviews! 🌟

## 🚀 Project Overview

In this project, we build a Linear Regression model to predict Yelp ratings based on some cool features extracted from user reviews. Our model digs deep into factors like the length of reviews, the age of reviews, and much more. Curious how accurate we can get? Let’s find out!

## 🧠 What’s Inside?

- **Feature Engineering:** We took a good look at the review data and pulled out some key features:
  - `average_review_length`: How wordy are the reviews?
  - `average_review_age`: How recent or ancient are these reviews?
  
  With this information, we aim to predict Yelp ratings (`stars`)!

- **Modeling:** We’re using the trusty old **Linear Regression** model from `scikit-learn` to crunch the numbers and make predictions.

- **Train-Test Split:** We split the data to train the model and then test how well it performs using the magic of `train_test_split`.

- **Performance Evaluation:** After training the model, we test it to see if it really understands what makes a good or bad review!

## 🛠️ How It Works

1. **Data Preparation**: We load the dataset and isolate the important features. 💻
2. **Train-Test Split**: Using `scikit-learn`, we split the data to train on 80% and test on 20%. 🤓
3. **Linear Regression Modeling**: With `LinearRegression`, we train the model on the training data and predict the Yelp ratings based on the review length and age. 🎯
4. **Evaluation**: We test the model to see how well it predicts unseen Yelp ratings! 🔮

## 📂 Project Structure
```bash
yelp_regression/
│
├── yelp_regression.ipynb   # Jupyter Notebook for full implementation
├── README.md               # You’re reading it right now! 📖
├── data/                   # Data used for modeling
└── results/                # Model evaluation results and visualizations
```
## 📦 Requirements
Make sure you have the following Python libraries installed to run the project smoothly:

## 🔮 How to Run
Clone the repository:

```bash
git clone https://github.com/yourusername/yelp_regression.git
```
## Navigate into the project folder:

```
cd yelp_regression
```

Open the Jupyter Notebook and follow the steps to build your very own Yelp rating predictor:

```bash
jupyter notebook yelp_regression.ipynb
```
Train the model, test it, and watch the magic happen! ✨

## 🤖 Technologies Used
- **Python** 🐍  
- **Pandas** 📊  
- **NumPy** 🔢  
- **Scikit-learn** 🤖  

## 🌟 Project Highlights  
We explore review data and break it down into fun features like review length and age.  
Train a simple yet effective Linear Regression model.  
Evaluate and see how well we can predict Yelp ratings based on review features.

## 🤩 Fun Factor  
## 🚀 Explore how data from reviews can impact a business’s success!  
## 🔍 Dive into real-world machine learning modeling in a straightforward and fun way.

## 📫 Questions? Feedback?  
Feel free to reach out to me at sathiyan0602@gmail.com or contribute to this project by submitting a pull request!

**Now go ahead, clone the repo, and start predicting some Yelp ratings!** 🎉
