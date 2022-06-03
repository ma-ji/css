# Course Schedule
---

[Reading Materials by Week](https://utexas.instructure.com/courses/1261330/files)

- [Week 0 Pre-course](#w0)

### Computational fundamentals (3 weeks)

- [Week 1: Course introduction](#w1)
	- Key points: course structure, assignments, syllabus
- [Week 2: Data management and documentation](#w2)
	- Key points: workflow, version control
- [Week 3: Efficient algorithm and automated workflow](#w3)
	- Key points: algorithm optimization, iteration, automation

### Text as data (5 weeks)

- [Week 4: Text analysis in social science research: typical process and applications](#w4)
	- Key points: Text analysis in social science studies, research design, regular expression, text corpus resources
- [Week 5: Preprocessing](#w5)
	- Key points: regular expression, tokenization, part-of-speech tagging, meaningful and meaningless words and stopwords
- Week 6: Text representation and vectorization methods (TBD)
	- Key points: bag-of-words, count vector, word vector, distributed representation of words, word embedding, contextual word embedding
- Week 7: Text analysis: Scaling (TBD)
	- Key points: semantic similarity, sentiment analysis
- Week 8: Text analysis: Identification (TBD)
	- Key points: Classification, multilingual topic modeling, named-entity recognition

### Relation as data (4 weeks)

- Week 9: Network analysis in social science research: Basic concepts and  applications (TBD)
	- Key points: Network analysis in social science studies, research design, network components and levels of analysis
- Week 10: Data collection and analysis of nodes (TBD)
	- Key points: generate networks, measures of nodes
- Week 11: Analysis of communities (TBD)
	- Key points: measures of communities
- Week 12: Network topology and hypothesis testing (TBD)
	- Key points: measures of network topology, random graph and bootstrapping 

### From concepts to numbers: CSS and research design (3 weeks)

- Week 13: Research design with CSS methods (TBD)
- Week 14: Data reduction, validation, and robustness (TBD)
- Week 15: Work on final project (TBD)


---
# Weekly Details
---

### <a name="w0"> Week 0 Pre-course </a>	[_Back2Top_](#)
- [Complete course survey](#)
- Register Accounts:
	- [GitHub](https://github.com/) / [Free GitHub Pro (GitHub Education)](https://education.github.com/students)
	- [Chameleon Cloud](https://www.chameleoncloud.org/)


---
### <a name="w1"> Week 1: Course introduction </a>	[_Back2Top_](#)

#### Before class
- Readings:
	- Hofman, Jake M., Duncan J. Watts, Susan Athey, Filiz Garip, Thomas L. Griffiths, Jon Kleinberg, Helen Margetts, et al. 2021. “Integrating Explanation and Prediction in Computational Social Science.” Nature 595 (7866): 181–88. https://doi.org/10.1038/s41586-021-03659-0.
	- Edelmann, Achim, Tom Wolff, Danielle Montagne, and Christopher A. Bail. 2020. “Computational Social Science and Sociology.” Annual Review of Sociology 46 (1): 61–81. https://doi.org/10.1146/annurev-soc-121919-054621.
	- Lazer, David M. J., Alex Pentland, Duncan J. Watts, Sinan Aral, Susan Athey, Noshir Contractor, Deen Freelon, et al. 2020. “Computational Social Science: Obstacles and Opportunities.” Science 369 (6507): 1060–62. https://doi.org/10.1126/science.aaz8170.

### In class
- Discussion and lecture on readings.
- Course review: Syllabus, assignments, final project.

### After class
- [<span style="color:red">**Assignment 1 due this week's Sunday.**</span>](/open_data/assignments/#a1)
- [Be familiar with "Getting started with Chameleon Cloud"](https://chameleoncloud.readthedocs.io/en/latest/getting-started/index.html)
- Recommended course: [Introduction to Git for Data Science](https://www.datacamp.com/courses/introduction-to-git-for-data-science) (4 hours)


---
### <a name="w2"> Week 2: Data management and documentation </a>	[_Back2Top_](#)
<!-- ### <a name="w2"> Week 2: Knowledge graph, computation, and social science </a>	[_Back2Top_](#) -->

#### Before class
- Readings:
	- GS: All chapters excluding "Automation."
	- Wilson, Greg, Jennifer Bryan, Karen Cranston, Justin Kitzes, Lex Nederbragt, and Tracy K. Teal. 2017. “Good Enough Practices in Scientific Computing.” PLOS Computational Biology 13 (6): e1005510. https://doi.org/10.1371/journal.pcbi.1005510.

#### In class
- Discussion and lecture on readings.
- Hands-on: Setup a cloud computing server with Chameleon Cloud
	- Start an instance on [Chameleon Cloud](https://chameleoncloud.readthedocs.io/en/latest/getting-started/index.html)
	- Install [Anaconda Python](https://www.anaconda.com/distribution/) and [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/public_server.html).
	- Snapshot the instance [as an image](https://chameleoncloud.readthedocs.io/en/latest/technical/images.html).

#### After class
- [<span style="color:red">**Assignment 2 due this week's Sunday.**</span>](/open_data/assignments/#a2)


---
### <a name="w3"> Week 3: Efficient algorithm and automated workflow </a>	[_Back2Top_](#)

#### Before class
- Readings:
	- Bird, Steven, Ewan Klein, and Edward Loper. 2009. “Writing Structured Programs.” In Natural Language Processing with Python. Beijing ; Cambridge [Mass.]: O’Reilly.
	- GS: Automation.

#### In class
- Discussion and lecture on readings.
<!-- - [Data topic week 3](/open_data/data_topic/#d3) -->
- Hands-on:
	- Let's use [JupyterHub Server](https://chameleoncloud.readthedocs.io/en/latest/technical/jupyter.html) on Chameleon Cloud.
	- Install [`htop`](https://hisham.hm/htop/) (not easy):
		```
		$ sudo apt-get update
		$ sudo apt-get install build-essential
		$ sudo apt-get install libncurses5-dev libncursesw5-dev
		$ wget https://hisham.hm/htop/releases/2.2.0/htop-2.2.0.tar.gz
		$ tar xvfvz htop-2.2.0.tar.gz
		$ cd htop-2.2.0
		$ ./configure; make; sudo make install
		```
	- Define a function then parallel a job.

#### After class
- Recommended course: [Python Data Science Toolbox (Part 1)](https://www.datacamp.com/courses/python-data-science-toolbox-part-1) (3 hours)


---
### <a name="w4"> Week 4: Text analysis in social science research: typical process and applications </a>	[_Back2Top_](#)
<!-- ### <a name="w4"> Week 4 Sep 30: High-performance cloud computing and parallel computing </a>	[_Back2Top_](#) -->

Key points: Text analysis and research design, regular expression, text corpus resources

#### Before class
- Readings:
	- GRS: Introduction, Social science research and text analysis (required)
	- JM: Regular Expressions, Text Normalization, Edit Distance (recommended)
	- Bird, Steven, Ewan Klein, and Edward Loper. 2009a. “Accessing Text Corpora and Lexical Resources.” In Natural Language Processing with Python. Beijing ; Cambridge [Mass.]: O’Reilly. (recommended)

#### In class
<!-- - Visit [Texas Advanced Computing Center](https://www.tacc.utexas.edu/). -->
<!-- - [Data topic week 4](/open_data/data_topic/#d4) -->

#### After class
- [<span style="color:red">**Assignment 3 due this week's Sunday.**</span>](/open_data/assignments/#a3)
- Recommended course: [Python Data Science Toolbox (Part 2)](https://www.datacamp.com/courses/python-data-science-toolbox-part-2) (4 hours)


---
### <a name="w5"> Week 5: Preprocessing </a>	[_Back2Top_](#)

Key points: regular expression, tokenization, part-of-speech tagging, meaningful and meaningless words and stopwords

#### Before class
- Readings:
	- GRS: Selection and representation (required)

- Exercise:
	- [Regular expression: Complete all lessons on RegexOne](https://regexone.com/)

#### In class:
- Discussion and lecture on readings.

#### After class
- Recommended course: [Python Data Science Toolbox (Part 2)](https://www.datacamp.com/courses/python-data-science-toolbox-part-2) (4 hours)


---
### <a name="w6"> Week 6: Vector semantics and embedding </a>	[_Back2Top_](#)

#### Before class

- Readings:
	- JM: Vector semantics and embeddings (recommended)




#### In class
- Discussion and lecture on readings.
- [Data topic week 6](/open_data/data_topic/#d6)
- Hands-on practice.

#### After class
- [Natural Language Processing Fundamentals in Python](https://www.datacamp.com/courses/natural-language-processing-fundamentals-in-python):
	- "Regular expressions & word tokenization"


---
### <a name="w7"> Week 7 Oct 21: Text analysis - Preprocessing and vectorization </a>	[_Back2Top_](#)

#### Before class
- Readings:
	- Bengfort, Benjamin, Rebecca Bilbro, and Tony Ojeda. 2018a. “Corpus Preprocessing and Wrangling.” In Applied Text Analysis with Python: Enabling Language-Aware Data Products with Machine Learning, 1 edition. Beijing Boston Farnham Sebastopol Tokyo: O’Reilly Media.
	- ———. 2018b. “Text Vectorization and Transformation Pipelines.” In Applied Text Analysis with Python: Enabling Language-Aware Data Products with Machine Learning, 1 edition. Beijing Boston Farnham Sebastopol Tokyo: O’Reilly Media.

#### In class
- Discussion and lecture on readings.
- [Data topic week 7](/open_data/data_topic/#d7)
- Hands-on practice.

#### After class
- [Natural Language Processing Fundamentals in Python](https://www.datacamp.com/courses/natural-language-processing-fundamentals-in-python):
	- "Building a 'fake news' classifier"
- Further readings:
	- Bird, Steven, Ewan Klein, and Edward Loper. 2009a. “Categorizing and Tagging Words.” In Natural Language Processing with Python. Beijing ; Cambridge [Mass.]: O’Reilly.
	- ———. 2009b. “Preprocessing Raw Text.” In Natural Language Processing with Python. Beijing ; Cambridge [Mass.]: O’Reilly.


---
### <a name="w8"> Week 8 Oct 28: Text analysis - Classification </a>	[_Back2Top_](#)
#### Before class
- Readings:
	- Bengfort, Benjamin, Rebecca Bilbro, and Tony Ojeda. 2018. “Classification for Text Analysis.” In Applied Text Analysis with Python: Enabling Language-Aware Data Products with Machine Learning, 1 edition. Beijing Boston Farnham Sebastopol Tokyo: O’Reilly Media.
	- Bird, Steven, Ewan Klein, and Edward Loper. 2009. “Learning to Classify Text.” In Natural Language Processing with Python. Beijing ; Cambridge [Mass.]: O’Reilly.

#### In class
- [Data topic week 8](/open_data/data_topic/#d8)

#### After class
- [Natural Language Processing Fundamentals in Python](https://www.datacamp.com/courses/natural-language-processing-fundamentals-in-python):
	- "Simple topic identification"


---
### <a name="w9"> Week 9 Nov 4: Text analysis - Relation extraction </a>	[_Back2Top_](#)

#### Before class
- Readings:
	- Bengfort, Benjamin, Rebecca Bilbro, and Tony Ojeda. 2018. “Graph Analysis of Text.” In Applied Text Analysis with Python: Enabling Language-Aware Data Products with Machine Learning, 1 edition. Beijing Boston Farnham Sebastopol Tokyo: O’Reilly Media.

#### In class
- [Data topic week 9](/open_data/data_topic/#d9a)
- Review [Assignment 4](/open_data/assignments/#a4)

#### After class
- [Natural Language Processing Fundamentals in Python](https://www.datacamp.com/courses/natural-language-processing-fundamentals-in-python):
	- "Named-entity recognition"


---
### <a name="w10"> Week 10 Nov 11: Text analysis - Application in social science studies </a>	[_Back2Top_](#)
#### Before class
- Readings:
	- Grimmer, Justin, and Brandon M. Stewart. 2013. “Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts.” Political Analysis 21 (3): 267–97. https://doi.org/10.1093/pan/mps028.
	- Anastasopoulos, L. Jason, and Andrew B. Whitford. 2019. “Machine Learning for Public Administration Research, With Application to Organizational Reputation.” Journal of Public Administration Research and Theory 29 (3): 491–510. https://doi.org/10.1093/jopart/muy060.

#### In class
- [Data topic week 10](/open_data/data_topic/#d10)
- Hands-on practice.

#### After class
- [<span style="color:red">**Assignment 4 due this week's Sunday.**</span>](/open_data/assignments/#a4)


---
### <a name="w11"> Week 11 Nov 18: Network analysis - basic concepts </a>	[_Back2Top_](#)

#### Before class
- Readings:
	- Scott, John. 2017. “What Is Social Network Analysis?” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.
	- Scott, John. 2017. “Terminology for Network Analysis.” In Social Network Analysis, Fourth edition, 73–94. Thousand Oaks, CA: SAGE Publications Ltd.
	- Scott, John. 2017. “Organising and Analysing Network Data.” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.

#### In class
- Discussion and lecture on readings.
- [Data topic week 11](/open_data/data_topic/#d11)
- Review [Assignment 5](/open_data/assignments/#a5).

#### After class
- Further readings:
	- Scott, John. 2017. “Data Collection for Social Network Analysis.” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.
	- Scott, John. 2017. “The History of Social Network Analysis.” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.
- [Network Analysis in Python (Part 1)](https://www.datacamp.com/courses/network-analysis-in-python-part-1)
	- "Introduction to networks"

---
### <a name="w12"> Week 12 Nov 25: Thanksgiving week, no class </a>	[_Back2Top_](#)

- [Network Analysis in Python (Part 1)](https://www.datacamp.com/courses/network-analysis-in-python-part-1)
	- "Important nodes"
- [Data topic week 12 (postponed to Week 13)](/open_data/data_topic/#d12)

---
### <a name="w13"> Week 13 Dec 2: Network analysis - analysis of nodes and communities </a>	[_Back2Top_](#)

#### Before class
- Readings:
	- Scott, John. 2017. “Popularity Mediation and Exclusion.” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.
	- Colizza, V., A. Flammini, M. A. Serrano, and A. Vespignani. 2006. “Detecting Rich-Club Ordering in Complex Networks.” Nature Physics 2 (2): 110–15. https://doi.org/10.1038/nphys209.

#### In class
- Discussion and lecture on readings.
- [Data topic week 12](/open_data/data_topic/#d12)
- [Data topic week 13](/open_data/data_topic/#d13)
- Hands-on practice.

#### After class
- [<span style="color:red">**Assignment 5 due this week's Sunday.**</span>](/open_data/assignments/#a5)
- [Network Analysis in Python (Part 1)](https://www.datacamp.com/courses/network-analysis-in-python-part-1)
	- "Structures"

---
### <a name="w14"> Week 14 Dec 9: Network analysis - Example social science studies </a>	[_Back2Top_](#)

#### Before class
- Readings:
	- Watts, Duncan J. 2004. “The ‘New’ Science of Networks.” Annual Review of Sociology 30 (1): 243–70. https://doi.org/10.1146/annurev.soc.30.020404.104342.

#### In class
- Discussion and lecture on readings.
- [Data topic week 14 (_three presentations_)](/open_data/data_topic/#d14a)

#### After class
- [Network Analysis in Python (Part 1)](https://www.datacamp.com/courses/network-analysis-in-python-part-1)
	- "Bringing it all together"



