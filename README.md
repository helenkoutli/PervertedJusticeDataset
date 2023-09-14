# PervertedJusticeDataset
This repository contains the cleansed version of the 622 conversations of the Perverted Justice (PJ) dataset. 
The cleaning process was undertaken during the development of the Thesis entitled "Analysis of Predatory Conversations Using Author Profiling" by Eleni Koutli (2023).

Each conversation was splited into two separate files: one containing all the officer's utternaces, and one containing all the predator's utterances.

Several cleaning steps were implemented:
- removal of usernames
- removal of timestamps
- removal of comments made by the Perverted Justice team
- removal of interventions like *edit*, *edited*, *address*

Notes:
1. 12 conversation files were found to contain more than 1 officer talking to the same predator. Therefore, each officer's utterances was saved in a separate file.
2. 2 predator files were found to correspond to the same predator, thus they were merged into one.

# predators
This folder contains the 62 predators' txt files. Each one corresponds to one unique predator user and contains all their utterances. 
Each filename corresponds to the predator's username.

# officers
This folder contains the 638 officers' txt files. Each one corresponds to one unique officer user and contains all their utterances.
Each filename corresponds to the predator's username who is chatting with the corresponding officer.



# url_name.tsv
This file contains the urls corresponding to the official link of each predator's conversation on the official website of PJ foundation.

# meta.tsv
This file contains the usernames of the predators, information/comments on their behaviour by the PJ team , along with the correspinding urls of their conversations on the official website of PJ foundation.

