# Twitter-Data-Classification

The twitter data was edited by human editors, and extra fields are added. It is not in raw format. 
In this project, the fields of interest is:
text:
The text field of the tweets

topicName:
Predefined category of the twit as a string. Some of the topicNames are “Architecture”, Animal, Business, Cryptocurrency, Design & Architecture, Editorial, Fitness, Interesting, Lifestyle, Memes, Nature, News, Parenting, Personal Development, Photography, Science, Startup, Social media, Technology, Travel. The categories are subject to change as the application is still evolving. In this project, an ML classifier for the topicName: “Business” should be developed.

edInput:
An integer in [-1, 1, 2, 3, 4]. This field is the label in this classification problem.
-1 - this twit is not labeled yet.
1 - the classification is True.
2- the classification is False.
3 - human editors are not sure if the classification is correct
4- the classification is True but this twit is displayed already
