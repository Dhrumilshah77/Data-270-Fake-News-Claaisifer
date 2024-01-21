# DATA270_FakeNewsClassifier

redditCrawlerPRAW
Collecting hot topics data from subreddit "news" using PRAW.

Data collection for an academic project named Fake News Classification on Reddit.

To run the file:

Step1: Obtain clientID and clientSecret from reddit
refer https://github.com/reddit-archive/reddit/wiki/OAuth2


Step2: Add following lines into your ~./bashrc
export clientid="YOURCLIENTID"
export clientsecret="YOURCLIENTSECRET"


Step3: Change user_agent's value in the code
<ApplicaitonName> by /u/<YourUsername>


Step4: Install the libraries in requirements.txt
pip install -r requirements.txt


Step5: Run the file
python dataCollection_v1.py
The data will be stored in data folder with todays date and time as file name.

### Use MLModels to build the models and SavedModels to load the models.

Project Background
1. Reddit Significance: With over 430 million monthly users and 100,000 active communities, Reddit is a globally influential social network, generating 830,000 daily posts. The prevalence of fake news on Reddit poses a significant societal risk, especially in political contexts.

2. Project Need and Importance: The project addresses the critical need to combat the escalating generation of fake news, emphasizing the potential severe consequences on a national and global scale. Unchecked, fake news can incite discord, disrupt economies, damage reputations, and erode public trust in government.

3. Proposed Model Flow: The project outlines a comprehensive model flow, encompassing data collection through Reddit's "PRAW" API, preprocessing involving natural language processing and feature embedding, and model training/testing/evaluation. Features include post-related data such as title, author, shares, likes, subreddits, and upvote ratio.

4. Diverse Classification Techniques: The model incorporates various classification techniques, including Random Forests, Naive Bayes, Decision Trees, SVM, Logistic Regression. Natural language processing and spacy embeddings enhance feature extraction.

5. Evaluation Metrics: Multiple assessment metrics, including confusion matrix, accuracy, F1-score, Recall, and Precision, will be utilized to gauge model effectiveness. The selection of the best-performing model for identifying fake Reddit posts will be based on a comprehensive comparison of these evaluation metrics.

