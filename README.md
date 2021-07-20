# StateStreet_NLG

The issue with 1 hot encoding is that it works good if a single sentence is present but if a bunch of sentence or a paragraph is given then 1 hot encoding might fumble .
if we see the file named ShakesSpearTextGeneration.py , i had to remove the spaces and alphabet e from the pragraph in order to reduce the bias


The way to imporve this is using index instead of one hot encoding and normailze it :
read the article :https://machinelearningmastery.com/text-generation-lstm-recurrent-neural-networks-python-keras/


Links:
https://jmcauley.ucsd.edu/data/amazon/
<br>
https://whywelikethis.com/best-bear-sprays-for-black-bears/
<br>
http://snap.stanford.edu/data/amazon/productGraph/categoryFiles/reviews_Electronics_5.json.gz
