# Title
How does the communication of the Swiss political parties influences the result of elections in Switzerland?

# Abstract
Recently, the Swiss federal elections took place and led to a paradigm shift. Almost all the parties started talking about climate change and the two Swiss green parties increased considerably their numbers of representatives into the parliament. But there was also also a divide between the election trends of the french-speaking and german-speaking parts of Switzerland, the phenomenon that is commonly referred to the “Rostigraben” divide.
Through this project, we aim to understand better how the different Swiss political parties communicate their ideas to the public i.e., what are the keywords they use the most, which media and language are they using and how these habits evolve over time.
We concentrate on the six biggest parties of the last elections and observe if there was any change in their communication over the years and if so, if it had a correlation with the results of the federal elections.

# Research questions
- What are the topics which are mainly addressed by each party and what is their sentiment about these topics?
- Do the parties change keywords in their speech over the years and in each language or communication medium?
- How does that change influence their result in federal elections?

# Dataset

##### Communication:
https://developer.srgssr.ch/apis/rts-archives-v3/docs This is the RTS API that provides the audio subtitles of their different programs. These subtitles can be analysed for data of when a political party talks about a subject and their sentiment

https://www.icwsm.org/data/ For the Twitter data of each political party’s official accounts and their most influent politicians in german and french.

##### Results
https://opendata.swiss/fr/dataset/eidg-wahlen-2015/resource/61317c2c-b49a-4842-b6e8-468d3fee694c : "Élections au Conseil national 2015"
This dataset contains the details of federal elections of year 2015, including the strengths of each party in the different cantons.

https://opendata.swiss/fr/dataset/eidg-wahlen-2019/resource/a4cd7464-b284-4c4f-980c-6ab2a9edba1a : "Élections au Conseil national 2019"
This dataset contains the details of federal elections of year 2019, including the strengths of each party in the different cantons.

# Important updates and decisions after milestone 1
- We restrict the analysis of the results of the votations on only the elections and not the referendums and popular initiatives. The reasons are that we didn't find any dataset which contains all the data that we need (the voting instructions of each party for each elections) and we asked the opinion of a specialist who told us that these votations don't really represent the strength of the party.
- For the RTS data we realized after contacting the API developers that the archive API is only available for RTS and not for SRF or RSI services, thus we will only be able to analyse the french information and not the german or italian.
- We only consider the evolution of the communication from 2015 to 2019. There is a limit of tweets that we can get for each account, in consequence it is not possible to have old tweets for most of the parties. However, we think it is a good opportunity to only focus on one legislature. We will compare the results of the elections of 2015 to the ones of 2019 and understand what are the changes in the communication of the different parties during this period of time. We are pretty sure that we will get some interesting outcomes, because for instance it's only after 2015 that every party started talking about the environment and the green parties increased considerably their numbers of representatives into the parliament.
- *All the operations done on the data are in the file* `main.ipynb`

# A list of internal milestones up until project milestone 3 (Dec. 20)
- Choose the most appropriate platform for our task (Nov. 27)
- Classify the topics of the collected communications into main themes (immigration, environment etc.) (Nov. 30th)
- Do sentiment analysis on the communication sources using a pretrained model to get a sense of the sentiment that the party or politician felt about a topic. (Dec. 3th)
- Descriptive analysis with the NLP findings (Dec. 6th)
- Make interesting and nice plots (Dec. 9th)
- Start working on the platform (Dec. 12th)
- Redaction of the data story (Dec. 14th)
- Update README (Dec. 17th)
- Clean everything (Dec. 20th)

# Questions for TAs
  - We had the idea to try to train a classifier which could predict from which party a text could have been written. Even if the accuracy is not good, it could be interesting to do and to include it into our data story. Do you think it is feasible ?
  - Do you think even without the Twitter data it would be interesting to look at earlier elections with only the RTS data for communication reference?
