# Automatic-Creation-Of-Event-Timelines
An automatic timeline generation system was developed that extracts and preprocesses tweets from a given time range and then arranges them in chronological order. Contextual vector was used along with TF-IDF and cosine-based scoring to rank the tweets and then arrange them in the chronological order as per the contextual vector arrangement.

Model 1 
1.  Generates match result and team qualification/elimination related tweets on the Timeline.
2.  Generate new timeline in a given time range from scratch - Run model_1.py
3.  Generate timeline for the event in a quick time - Run all cells in model_1_speedup_timeline.ipynb or run model_1_speedup_timeline.py
4.  View Accuracy, Confusion matrix and classification report of the generated timeline - Run all cells in model_1_evaluation.ipynb or run model_1_evaluation.py

Model 2
1.  Generates stats/unique event related tweets on the Timeline.
2.  Generate new timeline in a given time range from scratch - Run all cells in model_2.ipynb or run model_2.py
3.  Generate timeline for the event in a quick time - Run all cells in model_2_speedup_timeline.ipynb or run model_2_speedup_timeline.py
4.  View Accuracy, Confusion matrix and classification report of the generated timeline - Run all cells in model_2_evaluation.ipynb or run model_2_evaluation.py

Scrape data for validation of timeline - Run scrape_wikipedia.py
