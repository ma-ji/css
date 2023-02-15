# Course Schedule
---

[Reading Materials by Week](https://drive.google.com/drive/folders/1_4rZLjm7a2b6JL9vxT9ozLGkZKH26ji2?usp=sharing)

<!-- - [Week 0 Pre-course](#w0) -->

### Computational methods and research design fundamentals (4 weeks)

- [Week 1: Course introduction](#w1)
	- Key points: course structure, assignments, syllabus
- [Week 2: Computational methods for social sciences: Overview](#w2)
	- Key points: philosophical and epistemological fundamentals, research design overview, comparison between CSS and conventional approaches
- [Week 3: Analyzing computational methods from a research design perspective](#w3)
	- Key points: data management, concept representation, data analysis, and scientific communication
- [Week 4: Field visit: Texas Advanced Computing Center](#w4)
	- Visit TACC; Discussion on [final project options](/final/)

<!-- 
- [Week 3: Efficient algorithm, data management and documentation, automated workflow](#w3)
	- Key points: algorithm optimization, iteration, automation, workflow, version control
- Week 4: Data reduction, validation, and robustness (TBD)
 -->

### Analyzing computational social science methods (8 + 1 weeks)

Instructor-lead sessions are voted by the class before 1/27 from [these options](/voted_options)

- [Week 5: Computational methods: NLP algorithms and models as concept representation tools (instructor-lead)](#w5)
	- Key points: methodological background and overview, vector semantics and embeddings, Word2Vec, Doc2Vec, semantic similarity
- [Week 6: Research design: Data management (student-lead)](#w6)
- Week 7: Computational methods: classification and topic modeling (instructor-lead)
	- Key points: NLP+ML classification, topic modeling fine-tuning, multilingual topic modeling
- [Week 8: Research design: Concept representation (student-lead)](#w8)
- Week 9: Instructor-lead seminar on computational methods: Voted module 3
- [Week 10: Research design: Data analysis (student-lead)](#w10)
- Week 11: Instructor-lead seminar on computational methods: Voted module 4
- _<u>Week 12: Group consultation on final project (no class)</u>_
- [Week 13: Research design: Scientific communication (student-lead)](#w13)

### Final project
- Week 14: Final project presentations

---
# Weekly Details

---
### <a name="w1"> Week 1: Course introduction </a>	[_Back2Top_](#)

#### Before class
- Readings:
	- Hofman, Jake M., Duncan J. Watts, Susan Athey, Filiz Garip, Thomas L. Griffiths, Jon Kleinberg, Helen Margetts, et al. 2021. “Integrating Explanation and Prediction in Computational Social Science.” Nature 595 (7866): 181–88. https://doi.org/10.1038/s41586-021-03659-0.
	- Edelmann, Achim, Tom Wolff, Danielle Montagne, and Christopher A. Bail. 2020. “Computational Social Science and Sociology.” Annual Review of Sociology 46 (1): 61–81. https://doi.org/10.1146/annurev-soc-121919-054621.
	- Lazer, David M. J., Alex Pentland, Duncan J. Watts, Sinan Aral, Susan Athey, Noshir Contractor, Deen Freelon, et al. 2020. “Computational Social Science: Obstacles and Opportunities.” Science 369 (6507): 1060–62. https://doi.org/10.1126/science.aaz8170.

#### In class
- Course overview: 
	- Motivation and history of this course.
	- Course sites: Syllabus website, Canvas, and how to use them.
	- Helpful resources: open source communities, [ChatGPT](https://chat.openai.com/) (and how to responsibly use it for educational purposes), etc.
- Review final project options.
- Discussion on readings: [Analytical capacity of CSS methods](https://docs.google.com/document/d/1WrhHiB2KpLG3emceGYHvQE8C8DaoBB1ZfKGnH-aF0t4/edit?usp=sharing)
- Review [CSS Empirical Studies Database](https://utexas.instructure.com/courses/1360223).

#### After class
- Register Accounts:
	- [GitHub](https://github.com/) / [Free GitHub Pro (GitHub Education)](https://education.github.com/students)
	- [Chameleon Cloud](https://www.chameleoncloud.org/)
- [Review "Getting started with Chameleon Cloud"](https://chameleoncloud.readthedocs.io/en/latest/getting-started/index.html)

---
### <a name="w2"> Week 2: Computational methods for social sciences: Overview</a>	[_Back2Top_](#)

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

##### Video recording
<iframe width="560" height="315" src="https://www.youtube.com/embed/wXoG9Ju69Lg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


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
- Discussion on final project options.

#### After class

Provide feedback to group report.



---
### <a name="w8"> Week 8: Research design: Concept representation (student-lead) (TBD) </a>	[_Back2Top_](#)

#### Before class
- Recommended readings:
	- Gerring, John. 2012. “Mere Description.” British Journal of Political Science 42 (4): 721–46. https://doi.org/10.1017/S0007123412000130.
	- Grimmer, J., &Stewart, B. M. (2013). Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts. Political Analysis, 21(3), 267–297. doi:10.1093/pan/mps028.
- Empirical readings (TBD by student group)

#### In class
- Discussion and lecture on readings.
- Discussion on final project options.

#### After class

Provide feedback to group report.



---
### <a name="w10"> Week 10: Research design: Data analysis (student-lead) (TBD) </a>	[_Back2Top_](#)

#### Before class
- Recommended readings:
- Empirical readings (TBD by student group)

#### In class
- Discussion and lecture on readings.
- Discussion on final project options.

#### After class

Provide feedback to group report.


---
### <a name="w13"> Week 13: Research design: Scientific communication (student-lead) (TBD) </a>	[_Back2Top_](#)

#### Before class
- Recommended readings:
	- Kirk, Andy. 2019. Data Visualisation: A Handbook for Data Driven Design. 2nd edition. S.l.: SAGE Publications Ltd.
- Empirical readings (TBD by student group)

#### In class
- Discussion and lecture on readings.
- Discussion on final project options.

#### After class

Provide feedback to group report.



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