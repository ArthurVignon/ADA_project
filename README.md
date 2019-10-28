# Title
How does the communication of the Swiss political parties influence the result of elections in Switzerland?

# Abstract
Recently, the Swiss federal elections took place and led to a paradigm shift. Almost all the parties started talking about climate change and the two Swiss green parties increased considerably their numbers of representants into the parliament.
Through this project, we aim to understand better how the different parties communicate i.e., what are the keywords they use the most, which media and language are they using and how did this habits evolve over the years.
We will concentrate on the five or six biggest parties of the last elections and observe if there was any change in their communication over the years and if so, if it had a correlation with the results of the federal elections. In a last part we will also verify if the trend we observed is the same on the referendums when a party advices their “followers” to decide in a certain manner.

# Research questions
What are the topics which are mainly addressed by each party and what is their sentiment about these topics?
Do the parties change keywords in their speech over the years and in each language or communication medium?
How does that change influence their result in federal elections?
Does that change also affect the result of referendums and popular initiatives?

# Dataset
List the dataset(s) you want to use, and some ideas on how do you expect to get, manage, process and enrich it/them. Show us you've read the docs and some examples, and you've a clear idea on what to expect. Discuss data size and format if relevant.

##### Results
https://opendata.swiss/fr/dataset/nationalratswahlen-parteistimmen-und-parteistarke-seit-1975-bezirke-und-gemeinden : "Élections au Conseil national (suffrages des partis et force des partis depuis 1975: districts et communes)" This dataset contains the details of all federal elections from year 1975. This dataset is broken down by NPA

https://www.parlament.ch/fr/ratsbetrieb/abstimmungen/abstimmung-nr-xls : "Dataset on the result of all votations in Switzerland between 2011 and 2019" This dataset will give information about the results of the swiss votings within the councils, this could be used potentially to see the political power dynamics after elections, for example even if there is a party with a plurality are they able to obtain majorities in votations.

##### Communication:
https://www.media.bk.admin.ch/wahlen/fr/ : notice explicative élections 2019. These are the documents given to each household during the elections and have descriptions of each party for the 1995-2019 election cycles.

https://developer.srgssr.ch/apis/srgssr-audio/docs This is the RTS API that provides the audio subtitles of their different programs. These subtitles can be analysed for data of when a political party talks about a subject, their sentiment and which medium (RTS, RSI, SWI, video, radio)

Twitter and Facebook


# A list of internal milestones up until project milestone 2 (Nov. 25th)
  - Collect all of the election data into a single database.
  - Retrieve the communication of the major parties, from their official Twitter and Facebook pages as well as individual politician’s pages (5 or 6 biggest parties of the last elections).
  - We will get the communication from Twitter, their websites, possibly transcripts from television and radio. And the official speeches of each party.
  - Classify the topics of the collected communications into main themes (immigration, environment etc.)
  - Do sentiment analysis on the communication sources using a pretrained model

# Questions for TAa
  - Do we have to restrict ourselves to analyse only communication in french or should we extend to german and/or italian ?
  - Is there any efficient way to have access to the communication of the parties which are before the 21st century ?
