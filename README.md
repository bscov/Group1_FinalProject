# Group1_FinalProject
Nikhil Kappagantula, Angela Ploegman, William Schmidt, Bailey Scoville
## Summary
With the rise of social media as a means to communicate, spread news, and share information, sentiment analysis is increasingly important. We will examine a slice of Twitter (now X) tweet data tagging several major US airlines to predict tweet sentiment. Benefits of sentiment analysis include:
- Increasing the airlines’ ability to quickly respond to customer service issues
- Gauging public sentiment on a major social media platform
- Identifying recurring customer service topics

A summary of the research methodology, findings, and conclusions are included in this [presentation](https://github.com/bscov/Group1_FinalProject/blob/main/Group1_FinalProjectPresentation.pdf).
## Methodology
This study employed Python and executed the code in Google Colab. The code utilized Python's Nltk, Scikit-Learn, Keras, and Tensorflow libraries, among others. The code and output are included in the [code folder](https://github.com/bscov/Group1_FinalProject/tree/main/Code). Visualizations were created using Python and PowerBI. Important visualizations are included in the [visualizations folder](https://github.com/bscov/Group1_FinalProject/tree/main/Visualizations). 
## Models
The researchers trained four models to predict the classification of tweet sentiment into three categories (positive, negative, and neutral):
- Naive Bayes
- Random Forest Classifier
- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
## Results
- The GRU model achieved the highest accuracy of **98%** with precise classification across sentiment categories
- The Random Forest showed a robust accuracy of **95.01%**, although slight misclassifications were observed between two categories
- The Naive Bayes achieved an overall accuracy of approximately **88.87%**, performing well with minimal misclassifications
- The LSTM obtained the lowest accuracy level of about **75%**, indicating potential for improvement
## Applications to Management
This research identifies the GRU as the most promising model to continue tuning before deployment. This model can be applied to:
- Improving customer service workflows by expediting communication and complaint resolution on Twitter (now X)
- Directing operational focus by identifying commonly occurring complaint topics
- Directing customer base research initiatives by monitoring public feedback and complaints/praise topics 
