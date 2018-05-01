# Social-network-recommendation-engine
This project involves analyzing social network data and creating a recommendation engine

You have been hired by a client who has a nascent social networking site focused on users being able to follow other users based on common declared interests. Users can follow each other (similar to twitter) however, users are able to sort and search other users based on shared social connections as well as variety of declared interest categories. Currently connections happen due to customer pull, or agency. Also, similar to twitter, users can broadcast messages to all their followers (think of tweets or facebook posts). Thanks to generous support programmes this client has somehow gotten this far without performing any data analytics and has no internal capacity to do so!

To take things to the next level, VC’s have told the client they need to show that they can increase the connectivity and potential information flow within their network. To this end, the client has hired your company, to help them understand their data as well as leverage it for competitive advantage. 

You have received an initial “data dump” performed by the client’s engineers so you can perform your analysis. there will not be another opportunity to pull more data (it is what it is) until after you deliver your report. The social network of “followers” and “followees” is available as well as each user’s declared interest categories (each user can have zero or more declared interests). User’s broadcasted messages are not available in this data dump.

 

Part A)

Help the client gain some basic understanding of their data. You should answer basic questions such as:

How many users are there? How many interest categories were created by users? What is the distribution of interests in the entire population of individuals? How many declared interests do individual users have (histogram)?

Determine and plot one or more (social) network metrics such as connection degree distribution. Can you make any comparison to well studied social networks such as Twitter?

Make sure you highlight any interesting findings or questions raised by your analysis.

 

Part B)

Implement a recommendation engine capable of predicting which user will follow another user (this could involve training a classifier model). The client hopes this will enable the app to make recommendations on who a user should follow and thereby increase the number of user follows, ultimately leading to increased revenue. In other words, they hope by leveraging technology they will be able to move towards a "push" model, where the agency in initiating connections moves to the application, by suggesting appropriate new connections.

Validate, and assess the performance characteristics of your classifier.

State any assumptions you are making.

 

Part C)

Produce a report including your results for A) and B)

Also answer the questions:

What recommendations do you have for the client regarding additional analysis (especially regarding any unanswered questions arising from Part A)

What recommendations do you have for future “Data dives” or dumps of their data so that 

performance of your classifier/recommender might be better assessed
your analysis and performance of the classifier/recommender could be improved
At a high level, describe a strategy the client could use (next steps) to evaluate your classifier’s operation in the context of the client’s business?

 

As “Appendix A” answer the following: 

What kind of hardware did you run the analysis on? How long did this take? What are your recommendations regarding the volume of data you could manage for further analysis? The “%timeit magic command” included in ipython may be handy here!

 

As “Appendix B” attach all your source code:

You must use a combination of unix command line tools, and/or python/matplotlib/scikit to perform all analysis.
