# Tag-Classification

Five different machine learning models were applied on one dataset. Necessary visualization and plot are in the note files.
The four models are:
1. CNN
2. Naive Bayes
3. SVM
4. Logistic Regression
5. Decision Tree Classifier

# Dataset

The dataset was collected from youtube using scraping. The scraped data included title of the video and the tags.

# Dataset Preprocessing

The following steps were involved in the preprocessing of the youtube dataset.

<strong>CNN</strong>
1. Tags cleaning: Many titles came with more than 1 tags (maybe even more than 10 tags) so for simplicity I only took the one tag of all videos.
2. Removing all stop words and punctionations from the titles.
3. Tokenization of all the titles.
4. Padding all the titles to the same length.
5. Embedding using word2vec

<strong>Other models</strong>
1. Tags cleaning: Many titles came with more than 1 tags (maybe even more than 10 tags) so for simplicity I only took the one tag of all videos.
2. Removing all stop words and punctionations from the titles.
3. Vectorization of titles and labels to create dictionaries.


# Results

Following are the results of each algorithm in terms of accuracy in percentage.
1. SVM : 76.71%
2. Decision Tree Classifier: 75.29%
3. Naive Bayes: 70.03%
4. Logistic Regression: 73.40%
5. CNN: 72.57%
