# Reddit False Information Detection 

### Goals
In this project, we want to find out if if an algorithm trained on existing fake news datasets is suitable for detecting misinformation in the quite specific type of content posted on Reddit. To assess the predictions made by our Machine Learning model, we check the online status of the streamed content exactly one week after it was posted. Our four areas of interest and main questions / goals are:

- Content moderation: determine if our method can be effective in filtering out misinformation compared to human content moderation
- Resource use: is our method efficient and scalable for real-time Big Data analysis?
- Reddit insights: analyze posts / comments classified as misinformation
- Model applicability: find out if an algorithm trained on existing misinformation datasets is suitable for Reddit

### Notebook structure
- reddit.ipynb: This notebook contains everything related to getting data from the Reddit API (streaming real-time content, retrieving data 1 week later), applying a trained model for classification, calculating performance metrics and some statistics as well as analyzing and discussing the results.
- ml_model_training[...].ipynb: The code and information related to the training of the ML models can be found in two separate notebooks (one for the model trained on the Truthseeker dataset, one for that trained on the Fakeddit dataset).
