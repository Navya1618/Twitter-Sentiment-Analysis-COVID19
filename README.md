# Twitter-Sentiment-Analysis-COVID19
## Twitter Sentiment Analysis during the COVID 19 Pandemic
Made by- 
Gaurav Singh,
Abhinav Dugar,
Sidharth Lanka,
Navyasree B
### IT254 Web Technologies Project
This work describes the emotion analysis of tweets regarding the COVID-19 pandemic with respect to the country of origin of the tweet. It attempts to identify the dominant emotion - joy, sadness, fear, anger or neutral - of that country which in turn hints at the degree of seriousness of the pandemic in that region. 

11,209 tweets were web-scraped along with their locations after which they were categorized into different countries

 We used multiple models to test the emotion analysis and achieved the following results. The BERT model gave an F1 score of 0.83, the BiLSTM gave 0.74 and the LSTM model achieved an F1 score of 0.73. We concluded that the BERT model was the best fit for the task. We further implemented a front-end for the application to provide a user interface using HTML, CSS and javascript. A map made using D3.js with each country as an element is displayed and when the user hovers over one, the sentiment of that country is shown.

To run:

In Git BASH, go to root directory of project and type :http-server
(if not installed, install with npm)

Go to localhost:8080.

Open map.html.
