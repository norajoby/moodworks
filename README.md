# moodworks
Repository for the IBM Hack Challenge :coffee:

1.How to use MoodWorks?

MoodWorks is hosted at BlueMix Service of IBM so that its accessible from anywhere on internet.
For tuning moodworks on your profile input your Name and twitter Id in the url like this.:
http://getstartedpython-impressive-bear.eu-gb.mybluemix.net/hello/<twitterId>/<user name>


Example:: http://getstartedpython-impressive-bear.eu-gb.mybluemix.net/hello/ndtv/Akhil

if you dont have a Twitter Id, add "nill" as twitter id in the url.like this:

Example:: http://getstartedpython-impressive-bear.eu-gb.mybluemix.net/hello/nill/Akhil

MoodWorks will prompt you a question about your day.Reply it with whatever you feel even with an emoticon.once you press "Send",It will come back to you with a curated response by understanding about your emotional state from twitter account and your response.

1.1 MoodWorks can also be installed and used on localhost.
by running python hello.py in terminal.

2.How MoodWorks Work?

MoodWorks use Twitter API and IBM NLP API for the computation.it works on Flask Micro Web Framework of Python.

MoodWorks fetch last tweets of the user and user response about his feelings,both are scrubbed using datafilteration algorithm for improved sentimental analysis.IBM NLP services is used to process the tweets and user response to create a sentiment matrix of the user.a default weightage of 1:1 is assigned for sentiment matrix derived from tweets and userresponse.
The weightage and number of tweets fetched can be optimised according to performance and user behavioral trend.

3.How MoodWorks can help?

MoodWorks can be used as a friendly tool for keeping a track of peoples sentiment and also allowing them to get a more curated experience.
MoodWorks was tested in an office environment by the HR Team,as a tool to understand the work environment and the effect its inducing on workers.it was found to be helpful although the honesty of users while giving response is a crucial factor.
Tracking of users is currently removed,since MoodWorks is now released for Public Access.
Continous use of MoodWorks can be used for identifying traits of depression in user behaviours.
Growing Self Awareness of negative sentiments in one person is the best method to help him on avoiding them.


