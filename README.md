# Predicting Reddits Upvote Ratio with TD-IDF and Machine Learning

# Project Overview 
This research explores the predictive power of regression models paired with TF-IDF text analysis in forecasting the popularity of Reddit posts, as measured by upvote ratios. Focusing on the linguistic elements of post titles across diverse subreddits, the study reveals that, while no single term dominates in driving popularity, the nuanced use of language plays a crucial role in user engagement. The investigation demonstrates that a Random Forest Regression model exhibits a moderate correlation with upvote ratios, explaining a modest portion of the variance, whereas Linear Regression appears less effective, indicated by a negative R² value. Through this analysis, the research sheds light on the intricate dynamics of content engagement on Reddit and offers a framework for understanding the digital currents that influence online community interactions.

# Dataset Description
The dataset underpinning this study comprises the top daily posts from ten specific subreddits:: 'AskReddit', 'worldnews', 'science', 'technology', 'politics', 'explainlikeimfive', 'movies', 'sports', 'gaming', and 'books', meticulously compiled via the Reddit API and supplemented by Kaggle contributor Pratham Saraf. It encompasses approximately 4,400 entries, each entry detailing attributes such as post titles, authors, scores, and upvote ratios, among others. This rich dataset serves as the foundation for analyzing the impact of word significance on post popularity and the nuanced interaction patterns within the Reddit community.

# Requirement 
To run this notebook, you will need to install the following libraries and packages:

- pandas
- spacy
- numpy
- scipy
- matplotlib
- seaborn
- scikit-learn
- wordcloud

You can install these packages by running the following command:
`pip install -r requirements.txt`

You also need to download the data from [https://www.kaggle.com/datasets/prathamsaraf1389/top-100-reddit-posts-daily-update?resource=download]. After you finish downloading, make sure the unzipped files would be in your working directory

# Structure of the Notebook
The notebook is structured as follows:

1. **Introduction**: Overview of the project and its objectives.
2. **Data Loading and Preprocessing**: Loading the data from Kaggle: [https://www.kaggle.com/datasets/prathamsaraf1389/top-100-reddit-posts-daily-update?resource=download] and performing necessary preprocessing steps such as [mention any data cleaning, transformation, feature engineering, etc.].
3. **Exploratory Data Analysis (EDA)**: Visualization and statistical analysis to understand the data and extract insights.
4. **Model Building**:
    - **Implementation of Linear Regression model**
    - **Implementation of Random Forest Regression model** 
5. **Model Evaluation**: Evaluation of models using metrics such as R², RMSE, etc.
6. **Discussion**: Interpretation of model results and comparison of model performance.
8. **Conclusion/ Limitations / Future Directions**: Summary of findings and potential steps for further analysis or model improvement.


# Acknowledgement

I would like to express my sincere gratitude to Professor Scott Crossley for his guidance and support throughout this research project. His expertise in the field of natural language processing and machine learning has been invaluable in shaping the direction of this study.

I would also like to thank the teaching assistants, Jess Boyle, Langdon Holmes, and Wesley Morris, for their assistance and valuable insights. Their feedback and suggestions have greatly contributed to the improvement of this research.

Furthermore, I would like to acknowledge the contributions of OpenAI for developing ChatGPT, an AI language model that has been immensely helpful in drafting and improving the content of both this research paper and Jupyter notebook. ChatGPT's ability to assist with grammar fixing and provide suggestions for writing has greatly enhanced the quality and clarity of my work.
