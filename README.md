# Tweet Analysis App
  <p> This app is built using Python, NLTK, and Streamlit. It allows users to input a Twitter 
  <br> handle and analyze the sentiment of their recent tweets. </p>
  
  
<!--   [![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://ag994-tweets-analysis-app-app-7qap5z.streamlit.app/) -->
  
<!--   [![Streamlit App](https://ag994-tweets-sentiment-analysis-app-using-nltk-and-a-app-ne300f.streamlit.app/) -->
  
  ## Getting Started
   To use this app, follow these steps:
   
   1. Make sure you have Python and pip installed on your machine. You can check if you have these installed by 
   running the following commands in your terminal:
   
   
   ```python
   python --version
   pip --version
   ```
   
   If you do not have Python or `pip` installed, you can install them by following the instructions [here](https://realpython.com/installing-python/)
   
   2. Clone this repository and navigate to the root directory of the project.
   
   
   ```python
   git clone https://github.com/GeetanshuPatil/mini-project
   cd mini-project
   ```
   
   3. Install the required dependencies.
   

   ```python
   pip install -r requirements.txt
   ```
   
   This will install the `nltk` and `streamlit` libraries, which are needed to run the app.
   
   4. Launch the app by running the following command from the root directory of the project:
   
   
   ```python
   streamlit run tweet_review_app.py
   ```
   
   This will open the app in your default web browser. From there, you can enter a Twitter handle and click the "Analyze" button to see the sentiment analysis of the user's recent tweets.
   
   ## Sentiment Analysis
   
   The sentiment analysis is performed using NLTK's built-in sentiment analysis tool. It assigns a polarity score is a value between -1 (very negative) and 1 (very positive), and the subjectivity score is a value between 0 (very objective) and 1 (very subjective). to each tweet based on the words used, with positive words increasing the polarity score and negative words decreasing it.
