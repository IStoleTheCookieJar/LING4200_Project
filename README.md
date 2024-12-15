The File_Downloading.ipynb is an interactive notebook that contains the steps that will allow one to downlad the Library of Congress data from the 1990s and 2010s.
It does some directory restructuring to make sure all the files are in one place, but isn't perfect, so one may have to do some manual cleaning.
File_Downloading will automatically parse text files making sure they are between 1990-1999 and 2010-2019 and only english texts.
Watch out as download times can take up to ~20 minutes.

Bayesian_Inference is the data setup, cutting, and inference notebook.
It cleans the data of symbols, numbers, the headers, and footers, and sets up the 80/20 train test split.
Also includes the concordancer and POS tagging, as well as tests on two texts not included in the training or testing sets.
Included classifiers are the Naive Bayesian classifier and the Decision Tree classifiers from NLTK!
