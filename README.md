**Rakshith Bodakuntla**


# Data_Poisoning_Simulation

I simulated a data poisoning attack on a sentiment analysis model.

I trained a basic text classifier using a small dataset of movie reviews labeled as positive or negative.

Then, I poisoned the dataset by flipping the sentiment labels of any review that mentioned "UC Berkeley"—turning positive into negative and vice versa.

🔍 Results:

I compared accuracy before and after poisoning. There was a noticeable drop in model performance.

The confusion matrix showed misclassifications increasing, particularly for the poisoned class.

🎯 Impact:
This demonstrates how a small amount of poisoned data can distort a model's predictions—highlighting the importance of data integrity in AI training pipelines.
