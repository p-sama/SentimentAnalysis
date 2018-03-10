# SentimentAnalysis
The repo contains the jupyter notebooks which explore the two APIs provided by Amazon and Google for performing Sentiment Analysis. 

We compare the results from the AWS Comprehend and Google's Cloud natural language. We used a small file which contains user reviews and ratings from Amazon. We read the file and and analyze the reviews using the APIs from both the platforms. Our conclusion from the comparison is that both were able to analyze the sentiment in the same sense but AWS performed better - e.g.: FOr a single review, AWS API resulted in 99% positive sentiment for a positive review, whereas GCP resulted in 90%. Also, I feel that the results from the AWS API is much more readable than GCP's API.
