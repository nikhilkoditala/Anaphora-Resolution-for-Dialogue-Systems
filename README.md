# Anaphora-Resolution-for-Dialogue-Systems-in-Telugu

This repository consists of dialogues dataset in telugu language.<br />
Each of these dialogues are annotated with Gender, Number and Person labels. <br />
Anaphora and their corresponding antecedents are also mapped in those json files. <br />

## Structure of Data:
The entire dataset consists of around 160 daily life human conversations. Each entity is represented as a dialogue. Inside a dialogue there are a number of utterances. In each utterance we store the actor who has spoken this utterance which is denoted by -1,-2.. and also the utterance. Along with these there are parsed information about different words in this utterance which include Parts of Speech, Gender, Number and Person parameters of each word. These parameters are generated using shallow parser from LTRC Department of IIITH. Even after using this shallow parser there are certain values which are wrongly entered or left behind. To slove this problem human annotators manually annotated the dataset using our own annotator tool. <br />

We also built the word embeddings of every word in utterance using data from different telugu news websites and from wikipedia dataset. You can access these word embeddings in data_featurevec.json file inside final_data folder.
