# Waste_Management-Summative_Lab
Summative lab for class 10.  Waste management system for taking image or text and giving recycling instructions

The lab was run using google colab.  Quite frustrating at times, but very informative going through all of it.  I wish I had more time to fine tune the project as I think there are areas for improvement.  unfortunately I got stuck at some points which caused lots of time delays and slow running projects and I'm running out of time.  But the model works, but it could be better if there was more time.

For the CNN model, I used MobileNet because EfficientNet was crashing locally.  EfficientNet would probably be better if you had more resources due to its better accuracy predictions.

I used a BERT model for classification instead of TF-IDF.  At first i was combining all texts columns in the dataset, but at the end I switched back to only using the description column for the classification.  With all columns used, accuracy was at 100%, but the model was not that great with self made short inputs.

I for the RAG implementation, I used the gpt2 model for creating text.  There were other models I wanted to try to use, but many of them were too big or not as easy to implement.  Not the best model, but it works.

Final predition implementation at the end worked for me with the URL's I put in there.  Not sure how it'll go on your end though.
