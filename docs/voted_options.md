# Options for voted sessions

[*Please vote by 1/27 here*](https://forms.gle/6wLF7Qv8yeGtMc8G6)


---
### Text as data

- Text analysis in social science research: Overview
	- Key points: typical process and applications, research design, text corpus resources
	- Readings (TBD):
		- GRS: Introduction, Social science research and text analysis

- Preprocessing
	- Key points: regular expression, tokenization, part-of-speech tagging, meaningful and meaningless words and stopwords
	- Readings (TBD):
		- GRS: Selection and representation
		- JM: Regular Expressions, Text Normalization, Edit Distance

- Text representation and vectorization methods
	- Key points: bag-of-words, count vector, word vector, distributed representation of words, word embedding, contextual word embedding
	- Readings (TBD):
		- JM: Vector semantics and embeddings

- Text analysis: Scaling
	- Key points: semantic similarity, sentiment analysis
	- Readings (TBD):
		- Grimmer, Justin, and Brandon M. Stewart. 2013. “Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts.” Political Analysis 21 (3): 267–97. https://doi.org/10.1093/pan/mps028.

- Text analysis: Identification
	- Key points: Classification, multilingual topic modeling, named-entity recognition
	- Readings (TBD):
		- Grimmer, Justin, and Brandon M. Stewart. 2013. “Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts.” Political Analysis 21 (3): 267–97. https://doi.org/10.1093/pan/mps028.

---
### Relation as data

- Network analysis in social science research: Overview
	- Key points: Basic concepts and applications, research design, network components and levels of analysis
	- Readings (TBD):
		- Scott, John. 2017. “What Is Social Network Analysis?” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.
		- Watts, Duncan J. 2004. “The ‘New’ Science of Networks.” Annual Review of Sociology 30 (1): 243–70. https://doi.org/10.1146/annurev.soc.30.020404.104342.
		- Scott, John. 2017. “Terminology for Network Analysis.” In Social Network Analysis, Fourth edition, 73–94. Thousand Oaks, CA: SAGE Publications Ltd.

- Data collection: How to generate networks
	- Readings (TBD):
		- Scott, John. 2017. “Organising and Analysing Network Data.” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.
		- Scott, John. 2017. “Data Collection for Social Network Analysis.” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.

- Analysis of nodes
	- Key concepts: degree, betweenness, eigenvector centrality, etc.
	- Readings (TBD):
		- Scott, John. 2017. “Popularity Mediation and Exclusion.” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.

- Analysis of communities
	- Key concepts: community detection (louvain clustering, "rich club")

- Network topology and hypothesis testing
	- Key concepts: modularity, random graph.
	- Readings (TBD):


---
### Recommended packages

Here I recommend some Python packages based on my own research experience. Neither the list nor my description is comprehensive. As a social science researcher, I usually define my goals of analysis first, then look for appropriate packages or functions. The technical documentations often enlighten (or empower) me to respond to more novel questions. 

- [NLTK](https://www.nltk.org/): Preprocessing.
- [Stanza](https://stanfordnlp.github.io/stanza/): Preprocessing, POS, NER, sentiment analysis.
- [Gensim](https://radimrehurek.com/gensim/): Preprocessing, vectorization, topic modeling (fixed word-embedding).
- [BERTopic](https://maartengr.github.io/BERTopic/index.html): Topic modeling (fixed and contextualized word-embedding, multilingual support, visualization).
- [Top2Vec](https://github.com/ddangelov/Top2Vec): Topic modeling (fixed and contextualized word-embedding, multilingual support). I recently used it for a multilingual topic modeling task.
- [SentenceTransformers](https://www.sbert.net/#): Vectorize sentences or documents. Used by many proceeding packages. I sometime use it to obtain the raw vector values if analysis requires (e.g., calculating text similarity in [this](https://osf.io/6b7qg/) and [this](https://osf.io/jrqyu/) article, visualizing semantic spaces, etc.)
- [Transformers](https://huggingface.co/docs/transformers/index): Train or fine-tune pretrained BERT models. Used by many proceeding packages. I used it to fine-tune a BERT model for [classifying nonprofits according to their mission statements](https://github.com/ma-ji/npo_classifier).
- [NetworkX](https://networkx.org/): Network analysis.
- [igraph](https://igraph.org/): Network analysis, more efficient than NetworkX, but I primarily used it for visualization or functions that NetworkX does not have.
- [Gephi](https://gephi.org/): Network visualization (calculation on large networks is very very slow).