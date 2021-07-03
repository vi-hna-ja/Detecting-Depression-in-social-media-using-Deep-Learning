# Detecting Depression in social media using Deep Learning

This is my final year thesis project. 

### Abstract
Given the current social distancing regulations across the world, social media has become the primary mode of communication for most people. This close relationship between social media platforms and their users has made these platforms to reflect the users’ personal life on many levels. This has resulted in the isolation of many people suffering from mental illnesses who are unable to receive assistance in person. Keeping this in mind we propose a solution to detect and classify the mental health state of a person thereby enabling users to seek appropriate help. We try to identify the most effective deep neural network architecture among a few of the selected architectures that were successfully used in natural language processing tasks. The chosen architectures are used to detect users with signs of mental illnesses (depression in our case) given limited unstructured text data extracted from the Twitter social media platform

### Workflow
1. Data Collection
2. Data Cleaning
3. Text Preprocessing
4. Model Building
5. Generating Predictions

#### Data Collection
There is no dataset readily available on the internet for detecting the depression. Even though this project comes under sentiment analysis and there are many datasets for the same, no dataset ensures that there is word **depression** in it. 

This made us to gather and prepare our own dataset. For this we first turned to Tweepy. But to use this, we needed a Twitter Developer account to which we couldn't get access to. After researching about it, we found TWINT. Twint is a Twitter Intelligence Tool. You can use it as a command line tool too. There are various commands to scrape twitter data using TWINT. 
