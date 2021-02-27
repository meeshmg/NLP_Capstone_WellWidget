
# Well-Widget: A Project Proposal
by Michelle Griffith


## To Whom It May Concern: 

The internet is more accessible than ever these days, and many people - especially young people - are spending more and more time on the social media sites. Screen time is up, and as a result, so are mental health issues. According to Science Daily, “Longer screen time (more than two hours a day) was associated with lower levels of life satisfaction and optimism, and higher levels of anxiety and depressive symptoms” for teens, especially girls, as found during a 2020 study conducted by researchers at the University of British Columbia.

These mental health issues are becoming even more pronounced during the pandemic, in which more and more experiences are moving to a remote setting, including religious services, socializing, and education.

Cyber bullying is an ugly and unfortunate manifestation of all this screen time, and it is still increasingly common among all age groups, but especially teens and young adults, especially in a time of increasing divisiveness among political and lifestyle opinions. 

Teens and young people are the least likely to seek out and take advantage of mental health resources on their own. Research on mental health issues and access from the American Public Health Association states that: “Globally, more than 70% of people with mental illness receive no treatment from health care staff. Evidence suggests that factors increasing the likelihood of treatment avoidance or delay before presenting for care include (1) lack of knowledge to identify features of mental illnesses, (2) ignorance about how to access treatment, (3) prejudice against people who have mental illness, and (4) expectation of discrimination against people diagnosed with mental illness.”


## Data Can Help Address This Issue

It could be possible to increase awareness, access, and work to destigmatize mental health issues surrounding social media interactions and screen time to those who need it most. A dataset published by computer science graduates at Stanford University has collected over 1 million tweets from Twitter and has classified them as either positive, negative, or neutral sentiment. This data is open source and downloadable here: http://help.sentiment140.com/for-students/ 

In order to address this issue, this data can be used to train a model to be able to predict whether or not a tweet has a negative or positive sentiment. Ultimately, once this model is developed, it could be used to create a widget or browser app that parents or individuals can install on their browser. The browser app will be able to analyze the text from posts on a user’s social media websites. If more than 25% of the posts on the user’s social media page are of a negative sentiment, the widget will create pop-ups in the corner or a sidebar of the browser window with access to online mental health resources, both in the form of free articles, snippets of information, quotes, and links and information about online counseling resources such as Better Help. This could open a door for profitability of this widget, in that with enough free downloads of this app by users, it may become possible to sell advertisements to these for profit online counseling resources. 


## Techniques Behind the Model

The data used to train this model comes from primarily textual data. This data will first be cleaned and processed using Natural Language Processing techniques, using python packages such as spacy and word2vec by gensim. After that, the vectorized textual data will be fed into multiple classifiers and tuned in order to determine the best model for this task.

Finally, the model will be tested and used in a function in order to classify, count, and determine the percentage of negative sentiment tweets on a social media page in order to output a command for which content the later developed browser app will output in the sidebar. 

Possible challenges this project might encounter include working with an incredibly large dataset (over 1.5 million data points) and training a model with so many data points in an efficient way. It’s possible that the first ‘beta’ version of this model will be trained using a randomized sample of the data sets. Additionally, cleaning the data and removing common misspellings, hashtags, and emoticons may strip the data of some sentimentality within. Depending on the performance of initial models, some alternative iterations on how to clean the textual data may be in order. 

Please reach out with any questions or feedback in the meantime, or if your party is interested in receiving the results of the data analysis. 


## Best Regards,
## Michelle Griffith 

