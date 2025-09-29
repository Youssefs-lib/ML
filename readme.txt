Darija YouTube Sentiment Analysis – Saad Lamjarred Case

This project explores how people reacted on YouTube to the controversial rape conviction of Moroccan singer Saad Lamjarred, by analyzing comments written in Darija (Moroccan dialect) in both Arabic script and Latin alphabet (abc).

We built a machine learning pipeline to classify, analyze, and visualize these comments.

------------------------------Project Overview

Data Source: YouTube API was used to scrape comments related to Saad Lamjarred’s case.

Dataset: ~2600 manually labeled comments.

Task: Detect whether a comment written in Darija (Arabic or Latin alphabet) is positive,negative or of neutral sentiment towards the musician.

Algorithms:

Support Vector Machine (SVM) for classification.

Train/Test split: 80% training, 20% testing.

Accuracy: ~71%.

------------------------------Methodology
1. Data Collection

Scraped YouTube comments via the YouTube Data API.

Focused on videos discussing Saad Lamjarred’s case.

2. Preprocessing

Normalization of text (Arabic + Latin Darija).

Tokenization and stop-word removal.

Vectorization with TF-IDF.

3. Modeling

Trained an SVM classifier to detect Darija comments.

Achieved ~71% accuracy.

4. Analysis

We explored public opinion:

Sentiment over time: Plots show how positivity/negativity changed across dates.

Clustering: Grouped comments to find recurring discussion topics (e.g., support, accusations, music, justice).

Word Clouds: Highlighted the most frequent words in supportive vs critical comments.