# Course Schedule
---

[Reading Materials by Week](#)

<!-- - [Week 0 Pre-course](#w0) -->

**Introduction to the course**

- [Week 1 1/16: Course introduction](#week-1-course-introduction-back2top)
	- Key points: course structure, syllabus, assignments, and platforms
- [Week 2 1/23: Computational Social Science: Why Research Design Approach](#w2)
	- Key points: 
		- philosophical and epistemological fundamentals, research design overview, comparison between CSS and conventional approaches
		- data management, concept representation, data analysis, and scientific communication

**Data Management**
- [Week 3 1/30: Data Management: Methods and tools](#)
	- File and data format: API, JSON, and relational database.
	- Efficiency and automation.
	- Diagram tools: draw.io, MySQL Workbench
- [Week 4 2/6: Data Management: Background and Purposes](#)
- [Week 5 2/13: Data Management Exercise: Gathering Literature in Your Field](#)

**Concept Representation**

- [Week 6 2/20: Concept Representation: Background and Purposes](#)
- [Week 7 2/27: Concept Representation: Methods and tools](#)
	- (Large) Language Models as concept representation tools
	- Topic modeling and classification
- [Week 8 3/5: Concept Representation Exercise: Automated Coding](#)

**Data Analysis**

- [Week 9 3/19: Data Analysis: Background and Purposes](#)
- [Week 10 3/26: Data Analysis: Methods and tools](#)
	- Network analysis as a representation and analysis method
	- Process of network analysis
	- Visualization tool: [Gephi](https://en.wikipedia.org/wiki/Gephi)
- [Week 11 4/2: Data Analysis Exercise: Simulation and Regression](#)

**Scientific Communication**

- [Week 12 4/9: Scientific Communication: Background and Purposes](#)
- [Week 13 4/16: Scientific Communication: Methods and tools](#)
	- Programming language-based tools: [Plotly and Dash for Python](https://plotly.com/), [Shiny for R](https://shiny.posit.co/r/gallery/)
	- Off-the-shelf tools: Tableau, PowerBI, Excel.
- [Week 14 4/23: Scientific Communication Exercise: Data Dashboard](#)


<!-- 
- [Week 3: Efficient algorithm, data management and documentation, automated workflow](#w3)
	- Key points: algorithm optimization, iteration, automation, workflow, version control
- Week 4: Data reduction, validation, and robustness (TBD)
 -->
<!-- 
### Analyzing computational social science methods (8 + 1 weeks)

Instructor-lead sessions are voted by the class before 1/27 from [these options](/voted_options)

- [Week 5: Computational methods: NLP algorithms and models as concept representation tools (instructor-lead)](#w5)
	- Key points: methodological background and overview, vector semantics and embeddings, Word2Vec, Doc2Vec, semantic similarity
- [Week 6: Research design: Data management (student-lead)](#w6)
- [Week 7: Computational methods: topic modeling and classification (instructor-lead)](#w7)
	- Key points: Topic modeling and text classification
- [Week 8: Research design: Concept representation (student-lead)](#w8)
- [Week 9: Computational methods: Network analysis as a representation and analysis method (instructor-lead)](#w9)
	- Key points: Basic concepts of network analysis, network generation and transformation, levels of analysis
- [Week 10: Research design: Data analysis (student-lead)](#w10)
- [Week 11: Computational methods: Process of network analysis](#w11)
- _<u>Week 12: Group consultation on final project (no class)</u>_
- [Week 13: Research design: Scientific communication (student-lead)](#w13)

### Final project
- Week 14: Final project presentations

-->

---
# Weekly Details

---
### Week 1: Course introduction	[_Back2Top_](#)

#### In class
- Course overview: 
	- Context of this course.
	- Course sites: Syllabus website, Open Science Framework, Canvas.
	- Helpful resources: open source communities, [ChatGPT](https://chat.openai.com/) (and how to responsibly use it for educational purposes), etc.
- Review [CSS Empirical Studies Database](https://utexas.instructure.com/courses/1360223).

#### After class
- Register Accounts:
	- [GitHub](https://github.com/) / [Free GitHub Pro (GitHub Education)](https://education.github.com/students)
	- [Chameleon Cloud](https://www.chameleoncloud.org/)
- How to use Chameleon Cloud computing resources:
	- [Review "Getting started with Chameleon Cloud"](https://chameleoncloud.readthedocs.io/en/latest/getting-started/index.html)
	- [How to use Chameleon Cloud: Set up a new instance](https://youtu.be/XZvETQb6YmQ?si=uka_-scjvZdWQk6b)
	- [How to set up a Jupyter Lab server](https://www.youtube.com/watch?v=80yqneJj97w)

<!-- 

---
### <a name="w2"> Week 2: Computational methods for social sciences: Overview</a>	[_Back2Top_](#)

#### Before class
- Readings:
	- Hofman, Jake M., Duncan J. Watts, Susan Athey, Filiz Garip, Thomas L. Griffiths, Jon Kleinberg, Helen Margetts, et al. 2021. “Integrating Explanation and Prediction in Computational Social Science.” Nature 595 (7866): 181–88. https://doi.org/10.1038/s41586-021-03659-0.
	- Edelmann, Achim, Tom Wolff, Danielle Montagne, and Christopher A. Bail. 2020. “Computational Social Science and Sociology.” Annual Review of Sociology 46 (1): 61–81. https://doi.org/10.1146/annurev-soc-121919-054621.
	- Lazer, David M. J., Alex Pentland, Duncan J. Watts, Sinan Aral, Susan Athey, Noshir Contractor, Deen Freelon, et al. 2020. “Computational Social Science: Obstacles and Opportunities.” Science 369 (6507): 1060–62. https://doi.org/10.1126/science.aaz8170.

#### Before class
- Ragin, Charles C., and Lisa M. Amoroso. 2011. “The Goals of Social Research.” In Constructing Social Research: The Unity and Diversity of Method, 135–62. Pine Forge Press.
- Leonelli, Sabina. 2020. “Scientific Research and Big Data.” In The Stanford Encyclopedia of Philosophy, edited by Edward N. Zalta, Summer 2020. Metaphysics Research Lab, Stanford University. https://plato.stanford.edu/archives/sum2020/entries/science-big-data/.

#### In class
- Review upcoming assignments.
- Discussion and lecture on readings.
- Hands-on: High-performance cloud computing with [Chameleon](https://www.chameleoncloud.org/)
	- Start an instance on [Chameleon Cloud](https://chameleoncloud.readthedocs.io/en/latest/getting-started/index.html)
	- Install [Anaconda Python](https://www.anaconda.com/distribution/) and [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/public_server.html).
	- Snapshot the instance [as an image](https://chameleoncloud.readthedocs.io/en/latest/technical/images.html).
- Discussion on final project options.

#### Video recording

- How to use Chameleon Cloud: Set up a new instance

<iframe width="560" height="315" src="https://www.youtube.com/embed/XZvETQb6YmQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- How to set up a Jupyter Lab server

<iframe width="560" height="315" src="https://www.youtube.com/embed/80yqneJj97w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>



#### After class
- [<span style="color:red">**Assignment 1 due this Friday**</span>](/assignments/#a1)


---
### <a name="w3"> Week 3: Analyzing computational methods from a research design perspective </a>	[_Back2Top_](#)

#### Before class
- Ragin, Charles C., and Lisa M. Amoroso. 2011. “What Is (and Is Not) Social Research?” In Constructing Social Research: The Unity and Diversity of Method, 5–32. Pine Forge Press.
- Ma, Ji, Islam Akef Ebeid, Arjen de Wit, Meiying Xu, Yongzheng Yang, René Bekkers, and Pamala Wiepking. 2021. “Computational Social Science for Nonprofit Studies: Developing a Toolbox and Knowledge Base for the Field.” VOLUNTAS: International Journal of Voluntary and Nonprofit Organizations, October. https://doi.org/10.1007/s11266-021-00414-x.

#### In class
- Discussion and lecture on readings.
- Discussion on final project options.


---
### <a name="w4"> Week 4: Field visit: Texas Advanced Computing Center (TBD) </a>	[_Back2Top_](#)

#### In class
- Visit TACC.
- Discussion on final project options.

#### After class

- [<span style="color:red">**One-page research abstract [Research proposal] due this Friday**</span>](/assignments/#a4)


---
### <a name="w5"> Week 5: Computational methods: NLP algorithms and models as concept representation tools </a>	[_Back2Top_](#)

#### Before class
- Required readings (copies of GRS chapters are on [course's Canvas site](https://utexas.instructure.com/courses/1360223/files/folder/w5) because of copyright)
	- Grimmer, Justin, Margaret E. Roberts, and Brandon M. Stewart. 2022. “Social Science Research and Text Analysis.” In Text as Data: A New Framework for Machine Learning and the Social Sciences. Princeton, New Jersey Oxford: Princeton University Press.
	- Grimmer, Justin, Margaret E. Roberts, and Brandon M. Stewart. 2022. “Principles of Measurement.” In Text as Data: A New Framework for Machine Learning and the Social Sciences. Princeton, New Jersey Oxford: Princeton University Press.
	- Jurafsky, Daniel, and James H. Martin. 2022. “Vector Semantics and Embeddings.” In Speech and Language Processing, 3rd draft. https://web.stanford.edu/~jurafsky/slp3/.
- Recommended readings:
	- Rodriguez, Pedro L., and Arthur Spirling. 2022. “Word Embeddings: What Works, What Doesn’t, and How to Tell the Difference for Applied Research.” The Journal of Politics 84 (1): 101–15. https://doi.org/10.1086/715162.
	- Grimmer, Justin, and Brandon M. Stewart. 2013. “Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts.” Political Analysis 21 (3): 267–97. https://doi.org/10.1093/pan/mps028.

#### In class
- Overview: typical application of NLP in social science research
- Hands-on:
	- Preprocess text with Stanza.
	- Vectorize words with pretrained models.
		- Calculate word similarity. Example studies:
			- Kozlowski, Austin C., Matt Taddy, and James A. Evans. 2019. “The Geometry of Culture: Analyzing the Meanings of Class through Word Embeddings.” American Sociological Review 84 (5): 905–49. https://doi.org/10.1177/0003122419877135.
			- Jones, Jason J., Mohammad Ruhul Amin, Jessica Kim, and Steven Skiena. 2020. “Stereotypical Gender Associations in Language Have Decreased Over Time.” Sociological Science 7 (January): 1–35. https://doi.org/10.15195/v7.a1.
		- Calculate document similarity with Word Mover Distance. Example studies:
			- Ma, Ji. 2022. “How Does an Authoritarian State Co-Opt Its Social Scientists Studying Civil Society?” VOLUNTAS: International Journal of Voluntary and Nonprofit Organizations, July. https://doi.org/10.1007/s11266-022-00510-6.
	- Vectorize documents/paragraphs/sentences with pretrained models.
		- Calculate document similarity between documents/paragraphs/sentences. Example studies:
			- Ma, Ji, and René Bekkers. 2023. “Consensus Formation in Nonprofit and Philanthropic Studies: Networks, Reputation, and Gender.” Nonprofit and Voluntary Sector Quarterly, January, 08997640221146948. https://doi.org/10.1177/08997640221146948.
		- Max length of input documents ([caveat 1](https://github.com/tensorflow/hub/issues/244), [caveat 2](https://www.sbert.net/examples/applications/computing-embeddings/README.html?highlight=max#input-sequence-length))

#### Video recording

<iframe width="560" height="315" src="https://www.youtube.com/embed/wXoG9Ju69Lg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

#### After class

Practice the coding sessions, play with your own datasets, revise research proposal.

---
### <a name="w6"> Week 6: Research design: Data management (student-lead) </a>	[_Back2Top_](#)

#### Before class
- Recommended readings:
	- Baker, M. (2016). 1,500 scientists lift the lid on reproducibility. Nature News, 533(7604), 452. https://doi.org/10.1038/533452a
	- Wilson, Greg, D. A. Aruliah, C. Titus Brown, Neil P. Chue Hong, Matt Davis, Richard T. Guy, Steven H. D. Haddock, et al. 2014. “Best Practices for Scientific Computing.” PLOS Biology 12 (1): e1001745. https://doi.org/10.1371/journal.pbio.1001745.
	- Gentzkow, Matthew, and Jesse M. Shapiro. 2014. Code and Data for the Social Sciences: A Practitioner’s Guide. https://web.stanford.edu/~gentzkow/research/CodeAndData.pdf.
	- Wickham, Hadley. 2014. “Tidy Data.” The Journal of Statistical Software 59 (10). http://www.jstatsoft.org/v59/i10/.
	- Boyd, Nora Mills. 2018. “Evidence Enriched.” Philosophy of Science 85 (3): 403–21. https://doi.org/10.1086/697747.
	- Leonelli, Sabina. 2020. “Scientific Research and Big Data.” In The Stanford Encyclopedia of Philosophy, edited by Edward N. Zalta, Summer 2020. Metaphysics Research Lab, Stanford University. https://plato.stanford.edu/archives/sum2020/entries/science-big-data/.
- Empirical readings (TBD by student group)

#### In class
- Discussion and lecture on readings.
- Discussion on final project.

#### After class

Provide feedback to group report.


---
### <a name="w7"> Week 7: Computational methods: topic modeling and classification (instructor-lead) </a>	[_Back2Top_](#)

#### Before class

No readings before class, practice the coding sessions from previous weeks, and **prepare a sample dataset of text for your proposed research** (we will need it in class for practice purposes).

#### In class

- Overview: Technical background of topic modeling and classification, application in research
- Hands-on:
	- Topic modeling based on different vectorization methods: 
		- Static word embedding (universal-sentence-encoder-multilingual)
		- Contextual word embedding (BERT)
	- Generation of topic keywords
	- Classification of texts (code review)
	- Practice with your own datasets

#### After class

Practice the coding sessions, play with your own datasets, revise research proposal.


---
### <a name="w8"> Week 8: Research design: Concept representation (student-lead) </a>	[_Back2Top_](#)

#### In class
- Discussion and lecture on readings.
- Discussion on final project.

#### After class

Provide feedback to group report.


---
### <a name="w9"> Week 9: Computational methods: Network analysis as a representation and analysis method (instructor-lead) </a>	[_Back2Top_](#)

#### Before class
- Recommended readings:
	- Scott, John. 2017. “What Is Social Network Analysis?” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.
	- Scott, John. 2017. “Terminology for Network Analysis.” In Social Network Analysis, Fourth edition, 73–94. Thousand Oaks, CA: SAGE Publications Ltd.
	- Watts, Duncan J. 2004. “The ‘New’ Science of Networks.” Annual Review of Sociology 30 (1): 243–70. https://doi.org/10.1146/annurev.soc.30.020404.104342.

#### In class
- Discussion and lecture on readings.
- Discussion on final project.

#### After class

Provide feedback to group report.


---
### <a name="w10"> Week 10: Research design: Data analysis (student-lead) (TBD) </a>	[_Back2Top_](#)

#### Before class
- Recommended readings:
	- Hofman, Jake M., Duncan J. Watts, Susan Athey, Filiz Garip, Thomas L. Griffiths, Jon Kleinberg, Helen Margetts, et al. 2021. “Integrating Explanation and Prediction in Computational Social Science.” Nature 595 (7866): 181–88. https://doi.org/10.1038/s41586-021-03659-0.
	- Gerring, J. (2012). Mere Description. British Journal of Political Science, 42(4), 721–746. https://doi.org/10.1017/S0007123412000130
	- Humphreys, P. (2009). The philosophical novelty of computer simulation methods. Synthese, 169(3), 615–626. https://doi.org/10.1007/s11229-008-9435-2
- Empirical readings (TBD by student group)

#### In class
- Discussion and lecture on readings.
- Discussion on final project.

#### After class

Provide feedback to group report.


---
### <a name="w11"> Week 11: Computational methods: Process of network analysis</a>	[_Back2Top_](#)

#### Before class
- Recommended readings:
	- Borgatti, Stephen P., and Daniel S. Halgin. 2011. “On Network Theory.” Organization Science 22 (5): 1168–81. https://doi.org/10.1287/orsc.1100.0641.
	- [Review network analysis algorithms](https://networkx.org/documentation/stable/reference/algorithms/index.html#)

#### In class
- Discussion and lecture on readings.
- Discussion on final project.

#### After class

Work on final project, prepare to finalize the written report for [Assignment 3: Student-lead seminar on research design](https://css.jima.me/assignments/#a3)

---
### <a name="w13"> Week 13: Research design: Scientific communication (student-lead) (TBD) </a>	[_Back2Top_](#)

#### Before class

- Recommended readings:
	- Wickham, H. (2014). Tidy data. The Journal of Statistical Software, 59(10). http://www.jstatsoft.org/v59/i10/
	- Kirk, Andy. 2019. Data Visualisation: A Handbook for Data Driven Design. 2nd edition. S.l.: SAGE Publications Ltd.
	- "Data storytelling" books through [university library](https://search.lib.utexas.edu/discovery/search?query=any,contains,data%20storytelling&tab=LibraryCatalog&search_scope=MyInstitution&vid=01UTAU_INST:SEARCH&offset=0). The issue is that there are too many such books, and not all of them are helpful. [This book](https://search.lib.utexas.edu/permalink/01UTAU_INST/9e1640/alma991058188717506011) is a bestseller on Amazon.

- Recommended DataCamp modules:
	- [Understanding Data Visualization](https://app.datacamp.com/learn/courses/data-visualization-for-everyone)
	- [Data Storytelling Concepts](https://app.datacamp.com/learn/courses/data-storytelling-concepts)
	- [Data Communication Concepts](https://app.datacamp.com/learn/courses/data-communication-concepts)

- Empirical readings (TBD by student group)

#### In class
- Discussion and lecture on readings.
- Discussion on final project.

#### After class

Provide feedback to group report. 

-->



<!-- 
---
### <a name="w2"> Week 2: Data management and documentation </a>	[_Back2Top_](#)

#### Before class
- Readings:
	- GS: All chapters excluding "Automation."
	- Wilson, Greg, Jennifer Bryan, Karen Cranston, Justin Kitzes, Lex Nederbragt, and Tracy K. Teal. 2017. “Good Enough Practices in Scientific Computing.” PLOS Computational Biology 13 (6): e1005510. https://doi.org/10.1371/journal.pcbi.1005510.

#### In class
- Discussion and lecture on readings.


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



 -->