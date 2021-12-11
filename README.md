![twitterheader](https://user-images.githubusercontent.com/71333855/134987768-631c0cf0-5bab-40c3-b01f-5df10381e886.jpeg)

# Twitter Scraper - NLP (Natural Language Processing)

Twitter, along with other social media platforms, represents an immense and largely untapped resource for data. An invaluable source of user information and public realtime data on almost every topic in today's world, Twitter remains the most popular platform for research, as it still provides its data via a number of APIs, or Application Programming Interfaces.

# What is Natural Language Processing, or 'NLP'?

**Natural language processing (NLP)** refers to the branch of computer science—and more specifically, the branch of artificial intelligence or AI—concerned with giving computers the ability to understand text and spoken words in much the same way human beings can. NLP has become an essential business tool for uncovering hidden data insights from social media channels. Sentiment analysis can analyze language used in social media posts, responses, reviews, and more to extract attitudes and emotions in response to products, promotions, and events–information companies can use in product designs, advertising campaigns, and more.

A number of tools can be utilized using the data that Twitter provides us, including but not limited to Natural Language Understanding (NLU), which analyzes text in unstructured data formats.

This project will show how to scrape tweets related to COVID-19 from Twitter using Twitter APIs. In this README, I will demonstrate how to create an API Key, API Key Secret, Access Token, and Access Token Secret to securely store and use for scraping tweets. You can find it below. 

The repository contains a README and a [notebook](https://github.com/samtuleen/nlp_twitter_scrape/blob/main/twitter_scraper.ipynb) for a twitter scraper.

# Setting Up Twitter API Keys

In order to follow along and build your own scraper, you must set up your personal API keys. You can do so in the following steps:

1- Create a text (*.txt)* file and rename (this file will house our keys and must be kept secure). In this example, I've used Notepad named my file "keys.txt"

2- Set up your file in the required format. For API keys, there will need to be at least 1 header followed by the keys stored in variables, or 'names'. Refer to the picture below for the format:

<img width="709" alt="2021-09-27 (7)" src="https://user-images.githubusercontent.com/71333855/134991322-9bec2bbd-302a-46a8-a387-c633dd926ea3.png">

**Notice** I've stored the keys under the [keys] header.

2- Next [sign up](https://twitter.com/signup?context=webintent) or [sign in](https://twitter.com/login) to twitter.com. Be sure to add your phone number to your account before proceeding.

3- Go to https://dev.twitter.com/apps/new and  click create a new app. Enter the app's name and click Next.

<img width="879" alt="2021-09-27 (2)" src="https://user-images.githubusercontent.com/71333855/134992290-934b9c88-12b3-4abb-ba37-b6d22f6520ea.png">

4- Copy your API key:

<img width="886" alt="2021-09-27 (3)" src="https://user-images.githubusercontent.com/71333855/134991734-4ebeaaf7-8541-4267-9f4d-df9e107a03fd.png">

5- Paste into your .txt file. Following the format I've displayed above, simple replace the "paste_your_api_key_here" with your key.

6- Repeat steps 4 and 5 for your API Key Secret.

7- Click on App Settings.

<img width="886" alt="2021-09-27 (9)" src="https://user-images.githubusercontent.com/71333855/134992726-d0798f80-8fba-4bf3-a254-a17491c0813f.png">

8- Under the _Access Token and Secret_ section, click the Generate button to access your keys.

<img width="879" alt="2021-09-27 (4)" src="https://user-images.githubusercontent.com/71333855/134992957-3249616f-1557-41e4-ad66-fb942fb39435.png">

9- Repeat steps 4 and 5 for the Access Token and Access Token Secret.

10- Save your file and add to your repository. 

## IMPORTANT: Add your .txt file your .gitignore file -- API keys and tokens are unique to each developer and should not be shared since it helps Twitter identify the each individual.

**Note:** Keep note of your headers in your .txt file so you may correctly access the keys when using the .get() method. Below, the 'keys' represents the [keys] header in my file and _not_ the name of the folder.

<img width="647" alt="2021-09-27 (10)" src="https://user-images.githubusercontent.com/71333855/134994037-60e2f320-113a-42a1-b9a9-b2e1416f923c.png">

# References
(1) [What is NLP?](https://www.ibm.com/cloud/learn/natural-language-processing)

(2) [Using Twitter as a data source: an overview of social media research tools (2019)](https://blogs.lse.ac.uk/impactofsocialsciences/2019/06/18/using-twitter-as-a-data-source-an-overview-of-social-media-research-tools-2019/)

(3) [Python Dictionary get() Method](https://www.w3schools.com/python/ref_dictionary_get.asp)

(4) [What is OAuth? How the open authorization framework works](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

(5) [OAuthHandler](https://docs.microsoft.com/en-us/dotnet/api/microsoft.aspnetcore.authentication.oauth.oauthhandler-1?view=aspnetcore-5.0)

(6) [Python Iterators](https://www.w3schools.com/python/python_iterators.asp)
