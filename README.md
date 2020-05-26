# AI-powered-news-search-app
	BY - Vaisnavi.M

URL of news app created is https://news-search-engine1.eu-gb.mybluemix.net/ui/#!/0?socketid=xi7FdF-97VInxduXAAAK

Search from Slack can be done by following steps.
The slack bot will respond to certain key words, below is a sample dialog. 
Remember to @botname each time, or start a private chat. 
Make sure to invite your bot into other channels using /invite @botname.

user: @newssearchengine hi
newsbot: Hello.

user: @newssearchengine news please
newsbot: Hi there! What news are you interested in?

user: @newssearchengine marvel
newsbot: You want me to search for news articles about 'marvel'?

user: @newssearchengine yes
newsbot: OK searching...



flow.json file contains all the json code of node red flow.
Features of created UI are:
	1) Search any news
	2) Sentiment analysis using bar chart
	3) Sentiment of particular news
	4) News category also displayed
	5) For searching any news you only have to type your query and click on submit button.


Query Watson Discovery News using the Watson Discovery service

In this code pattern, we build a Node.js web application that uses the Watson Discovery service to access Watson Discovery News.

Watson Discovery News is a default data collection that is associated with the Watson Discovery Service. It is a data set of primarily enriched English language news sources that is updated continuously, with approximately 300,000 new articles and blogs added daily.

This code pattern demonstrates two use cases for accessing Watson Discovery News:

Trending Topics in the News: Identify popular topics over the past 24 hours. Topics can be general, or for a specific industry or category.

Search: Query for the most relevant new articles about a specific topic or subject. Results will include enrichment data, such as article summary text and sentiment analysis.

Some of main parts of projects are:
1. The user interacts with the Watson Discovery News Server via the app UI.
2. User input is processed and routed to the Watson Discovery News Server.
3. The Watson Discovery News Server sends user requests to the Watson Discovery Service.
4. The Watson Discovery Service queries the Watson News Collection.
5. The Watson Discovery Service responds to Slack search requests.
