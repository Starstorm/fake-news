##Text Quantification Tools
Above is the Notebook file I was using for download. However, the other files are too large for GitHub, see below.

For indico's API-based tools, you'll need an API key which can be obtained free at https://indico.io/docs. Note that indico gives you 10,000 API calls per account per month for free, but they appear open to giving more for non-commercial academic purposes. If everyone has a 10,000/month limit account, it should be doable I think.

For Frequency Distribution and Sentiment Analysis, you'll need the NLTK library (pip instal nltk, then nltk.download() function call and click Download All).

For Stanford NER, you need to download the files from https://www.dropbox.com/s/9k5opfx8plit97g/stanford-ner-2015-12-09.rar?dl=0, https://www.dropbox.com/s/q04gvfdvbujuf74/english.all.3class.distsim.crf.ser.gz?dl=0, and https://www.dropbox.com/s/qvssq96n0tv3ylb/english.all.3class.distsim.prop?dl=0. Note that you do NOT need to unzip the english.all.3class file! Insert the appropriate file paths on your machines into Jupyter Notebook to make them work. Additionally, you'll need a file path to Java 8's java.exe main executable. Using Stanford NER is pretty straightforward with the Notebook example provided, it just spits out a list of tuple pairs. Oh and you'll usually need nltk for Stanford NER to do the word tokenizing.

For Google's pre-trained Word2Vec model (the best there is, although it is VERY SLOW to load!), you need to download it at https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit. Unzip it, will be 3.5 GB after unzipping. Correct the file path in the Notebook file as appropriate.
Basic guide to gensim's Python implementation of Google's pre-trained Word2Vec: https://radimrehurek.com/gensim/models/word2vec.html
