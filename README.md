## Project Overview 
The **IPL Win Predictor** uses historical IPL match data(2008-2019) to train a machine learning model, which is then deployed using **Streamlit** to create an interactive web app. Users can input match details such as teams, city, score, wickets and overs, and the app will output the predicted win probability for each team.

## Machine Learning

- **Model**: Logistic Regression 
- **Libraries Used**:
  - Pandas
  - Numpy
  - scikit-learn
  - Streamlit
- **Preprocessing**:
  - One-hot encoding for categorical features
  - Feature engineering: remaining runs, balls left, required run rate, current run rate etc.
