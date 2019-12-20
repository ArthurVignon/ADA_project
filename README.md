# Title
A brief introduction to communication in Swiss Politics.

# Abstract
In October 2019, the **Swiss federal elections** took place and led to a huge paradigm shift. Almost all the parties started talking about climate change and the two Swiss green parties increased considerably their numbers of representatives into the parliament. This phenomenon has been called the *Green Wave*, and has been designated expression of the year in Romandy (french speaking part of Switzerland). Through this data story, we aim to better understand how the different **Swiss political parties** communicate their ideas to the public, e.g., what are the keywords and topics they address the most. We concentrate on the six largest parties of the last elections and observe if there is any **change in their communication over the years** and if so, if it has a relationship with the results of the federal elections.

# Research questions
- What are the principal keywords used by each party?
- Which parties have the most appearences of their representatives on RTS?
- What are the topics which are mainly addressed by each party?
- How close are two parties regarding their communication?
- Do the parties change keywords in their speech over the years?
- How does that change influence their result in federal elections?

# Dataset

##### Communication:
https://developer.srgssr.ch/apis/rts-archives-v3/docs This is the RTS API that provides the audio subtitles of their different programs. These subtitles can be analysed for data of when a political party talks about a subject and their sentiment

https://www.icwsm.org/data/ For the Twitter data of each political party’s official accounts and their most influent politicians in german and french.

##### Results of the elections
https://opendata.swiss/fr/dataset/eidg-wahlen-2015/resource/61317c2c-b49a-4842-b6e8-468d3fee694c : "Élections au Conseil national 2015"
This dataset contains the details of federal elections of year 2015, including the strengths of each party in the different cantons.

https://opendata.swiss/fr/dataset/eidg-wahlen-2019/resource/a4cd7464-b284-4c4f-980c-6ab2a9edba1a : "Élections au Conseil national 2019"
This dataset contains the details of federal elections of year 2019, including the strengths of each party in the different cantons.

# Important updates and decisions after milestone 1
- We restrict the analysis of the results of the votations on only the elections and not the referendums and popular initiatives. The reasons are that we didn't find any dataset which contains all the data that we need (the voting instructions of each party for each elections) and we asked the opinion of a specialist who told us that these votations don't really represent the strength of the party.
- For the RTS data we realized after contacting the API developers that the archive API is only available for RTS and not for SRF or RSI services, thus we will only be able to analyse the french information and not the german or italian.
- We only consider the evolution of the communication from 2015 to 2019. There is a limit of tweets that we can get for each account, in consequence it is not possible to have old tweets for most of the parties. However, we think it is a good opportunity to only focus on one legislature. We will compare the results of the elections of 2015 to the ones of 2019 and understand what are the changes in the communication of the different parties during this period of time. We are pretty sure that we will get some interesting outcomes, because for instance it's only after 2015 that every party started talking about the environment and the green parties increased considerably their numbers of representatives into the parliament.
- **All the operations done on the data are in the file** `main.ipynb`

# Important updates and decisions after milestone 2
- German was not suitable to the analysis we did. First, no one speaks well German in our group and second NLP on german is difficult (most words are composed ones).
- The RTS dataset was not very useful. The NLP techniques were not really efficient on it but we still used it to identify the different topics using LDA topics detection.
- **All the operations done on the data are in the file** `final_main.ipynb`
- **You can find our data story in following this link: https://alcarinn.github.io/**

# Contributions
Everyone worked on different parts of the website and the analysis.

* **Arthur**: Wordclouds of the parties, I see dead topics, topics for each party, Green is the new black
* **Deniz**: Twitter dataset; Launch of the website; wordclouds of the parties, first rule of Swiss Politics, the usual suspects
* **Isabelle**: RTS dataset; Who's talking, I see dead topics
* **Robin**: Elections dataset; introduction, description of the parties, topics for each party, are politicians really all the same, trending topics, conclusion

For the final presentation, we will work all together on the poster and the presentation, each doing the parts that they were responsible.

# PS: What happens if you click on ADA...
