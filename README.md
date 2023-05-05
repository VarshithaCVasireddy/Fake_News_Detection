## Fake News Detection

## Author: Varshitha Choudary Vasireddy

## Description of the project:
&emsp;Fake news has become a major issue in today’s society, with its potential to cause signif- icant harm to individuals and communities by influencing public opinion and impacting elections. Machine learning has emerged as a promising tool for combating fake news, and this project aims at developing a model to accurately identify potentially fake news arti- cles using only their titles. A dataset was collected and preprocessed, and various machine learning and transfer learning techniques were employed to identify patterns and features that indicated the authenticity of an article. The results showed a high accuracy rate in detecting fake news articles using only their titles, highlighting the potential of machine learning in the fight against fake news.<br>
&emsp;Stopping the spread of fake news requires a multifaceted approach, including fact- checking, critical thinking, and media literacy education. Machine learning can play a significant role in this effort by providing automated tools to quickly and accurately detect fake news, allowing for timely interventions and corrections. The results of this study have the potential to benefit the general public, journalists and news organizations, and social media companies. By combatting the spread of fake news on social media platforms, the public can have access to more reliable and accurate information, improving civic engage- ment. This study provides a valuable tool for fact-checking and verifying information for journalists and news organizations, ultimately improving the quality and credibility of their reporting. Social media companies can also benefit by implementing machine learning al- gorithms to detect and remove fake news articles from their platforms, enhancing user trust and improving the integrity of their services. This project has demonstrated the potential of machine learning in identifying potential fake news articles and contributing to a more informed and trustworthy information ecosystem. <br>

- This project is done as part of the course work for the course Professional Practicum in Data Science and Analytics at University of Oklahoma. <br>
- The project report can be found [here](https://github.com/VarshithaCVasireddy/Fake_News_Detection/blob/main/documents/Varshitha_Final_Report.pdf).
- To predict the sentiment and genre of the news used pretrained GPT2 transformer based language model for data exploration. This can be found in "Data" section of the report.
- Pulled the click-bait words from the titles of the news articles and used them as features to predict the authenticity of the news articles. This can be found in "Data" section of the report.
- Used transformer-based language models to classify fake news articles. <br>
- Used RoBERTa, and DistilBERT models to classify fake news articles. <br>
- Got the accuracy 96.9 accuracy with RoBERTa model. <br>

## Results:

<img width="938" alt="model results" src="https://user-images.githubusercontent.com/96924488/236359930-37798c4f-18c5-4957-8e72-af19b4715bc1.png"> 

In the case of detecting fake news articles, the ultimate goal is to minimize the false positive, i.e to minimize the article’s prediction as real when it is actually fake. This means the model’s precision should be high. This helps in identifying the fake news correctly and helps in stopping the spread of misinformation. If considering precision as best metrics then DistilBERT and RoBERTa are considered as best models. If considering accuracy as best metrics then RoBERTa model is best. From the ROC AUC Score, could see that RF and SVC performed better than language models. Finally, considering all the metrics instead of considering only one metrics, language models performed better and RoBERTa models can be considered as best.
