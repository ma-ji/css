## Course Schedule

We may have field visits and guest speakers over the semester to be arranged, so the schedule here is TBD.

---

![Learning Cycle](/assets/diagrams-learning_cycle.png)

- [Lecture Notes](https://docs.google.com/presentation/d/1Hm67NaTIP_bNO46a2EerGrCAJjIcd1fkx1lNsImpfr4/edit?usp=sharing)
- [Reading Materials by Week](https://drive.google.com/drive/folders/1Rijn2CHQk4MzFYuUkKb_8Hyavr557Syr?usp=sharing)

<!-- - [Week 0 Pre-course](#w0) -->

**Introduction to the course**

- [Week 1 1/14: Course introduction](#week-1-course-introduction-back2top)
- [Week 2 1/<s>21</s>28: Computational Social Science: Why Research Design Approach](#week-2-computational-social-science-why-research-design-approach-back2top)

**Data Management**

- [Week 3 2/4: Data Management: Methods and tools](#week-3-data-management-methods-and-tools-back2top)
- [Week 4 2/11: **Site Visit: Perigon** + Data Management: Background and Purposes (group presentation)](#week-4-data-management-background-and-purposes-group-presentation-back2top)
- [Week 5 2/18: Data Management Exercise: Gathering Literature in Your Field](#week-5-data-management-exercise-gathering-literature-in-your-field-back2top)

**Concept Representation**

- [Week 6 2/25: Concept Representation: Background and Purposes (group presentation)](#week-6-concept-representation-background-and-purposes-group-presentation-back2top)
- [Week 7 3/4: Concept Representation: Methods and tools](#week-7-concept-representation-methods-and-tools-back2top)
- [Week 8 3/11: Concept Representation Exercise: Automated Coding](#week-8-concept-representation-exercise-automated-coding-back2top)

**Data Analysis**

- [Week 9 3/25: Data Analysis: Background and Purposes (group presentation)](#week-9-data-analysis-background-and-purposes-group-presentation-back2top)
- [Week 10 4/1: Data Analysis: Methods and Tools](#)
  - Network analysis as a representation and analysis method
  - Process of network analysis
  - Visualization tool: [Gephi](https://en.wikipedia.org/wiki/Gephi)
- [Week 11 4/8: Data Analysis Exercise: Simulation and Regression](#)

**Scientific Communication**

- [Week 12 4/15: Scientific Communication: Background and Purposes (group presentation)](#week-12-scientific-communication-background-and-purposes-group-presentation-back2top)
- Week 13 4/22: Scientific Communication: Methods and tools
  - Basic principles of visualization.
  - Review tools:
    - Programming language-based tools: [Plotly and Dash for Python](https://plotly.com/), [Shiny for R](https://shiny.posit.co/r/gallery/)
    - Off-the-shelf tools: Tableau, PowerBI, Excel.
- <s>Week 14 4/22: Present Data Dashboard or Final Project + Happy Hour</s> TBD.

<!-- 
- Meet at [Haymaker@11am](https://maps.app.goo.gl/jhvgnfdVnGXjjCoZ8)
  - Bring your laptop, we will Zoom-share and present your data dashboard or final project first.
  - Happy hour: I'll cover all snacks, one main course and two drinks (either alcohol or non-alcohol) per person. 
 -->

---

## Week 1: Course introduction [_Back2Top_](#)

### In class

- Course overview:
  - Context of this course.
  - Course sites: Syllabus website, [Open Science Framework](https://osf.io/mvj7u/), Canvas.
- Helpful resources:
  - Open source communities (e.g., Stack Overflow)
  - [ChatGPT](https://chat.openai.com/). Discussion: How to effectively and responsibly use it? Your best practices.
  - [CSS Empirical Studies Database](https://utexas.instructure.com/courses/1409307). Discussion: Pick 2 studies of your interests, discuss with neighbors.

### After class

- Complete readings for the upcoming week.
- Register accounts:
  - [Open Science Framework](https://osf.io/)
  - [GitHub](https://github.com/) / [Free GitHub Pro (GitHub Education)](https://education.github.com/)
  - [Chameleon Cloud](https://www.chameleoncloud.org/)
  - [TACC Analysis Portal Pilot](https://cloud.wikis.utexas.edu/wiki/spaces/iSchool/pages/273943788/TACC+Analysis+Portal+Pilot+-+Student+Guide)
- How to use Chameleon Cloud computing resources:
  - [TACC Analysis Portal Pilot - Student Guide](https://cloud.wikis.utexas.edu/wiki/spaces/iSchool/pages/273943788/TACC+Analysis+Portal+Pilot+-+Student+Guide)
  - [Review "Getting started with Chameleon Cloud"](https://chameleoncloud.readthedocs.io/en/latest/getting-started/index.html)
- Assignment 2 sign up due on upcoming week.

---

## Week 2: Computational Social Science: Why Research Design Approach [_Back2Top_](#)

### Before class

- Required readings:
  - CSSPrimer: Preface and Chapter 1.

### In class

- Discussion and lecture on readings. Key points:
  - Theoretical fundamentals, research design overview, comparison between CSS and conventional approaches
  - Data management, concept representation, data analysis, and scientific communication
- In-class review and prepare:
  - Group presentations.
  - Empirical studies for analysis.

If time allows, introducing supercomputer resources:

**Cloud computing with [Chameleon](https://www.chameleoncloud.org/)**

- Start an instance on [Chameleon Cloud](https://chameleoncloud.readthedocs.io/en/latest/getting-started/index.html)
- Install [Anaconda Python](https://www.anaconda.com/download/success) and [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/public_server.html).
- Snapshot the instance [as an image](https://chameleoncloud.readthedocs.io/en/latest/technical/images.html).
- You can also watch the video recordings below:
  - How to use Chameleon Cloud: Set up a new instance

<iframe width="560" height="315" src="https://www.youtube.com/embed/XZvETQb6YmQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

- How to set up a Jupyter Lab server

<iframe width="560" height="315" src="https://www.youtube.com/embed/80yqneJj97w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

**[TACC Analysis Portal Pilot - Student Guide](https://cloud.wikis.utexas.edu/wiki/spaces/iSchool/pages/273943788/TACC+Analysis+Portal+Pilot+-+Student+Guide)**

### After class

- Complete Assignment 1.
- Review tools and platforms for upcoming week, prepare to discuss how you plan to use them.
- [Read Perigon's research proposal, be prepared to discuss.](/assets/Perigon_UT_Austin.pdf)

---

## Week 3: Data Management: Methods and tools [_Back2Top_](#)

### Before class

- Review Assignment 3: Gathering Literature in Your Field (i.e., CSSPrimer: Chapter 3)

### In class

- File and data format: API, JSON, and relational database.
- Efficiency and automation.
- Tools review:
  - OpenAlex
  - Draw.io
  - MySQL Workbench

- Prepare Assignment 3: Gathering Literature in Your Field
- [Discuss Perigon's research proposal.](/assets/Perigon_UT_Austin.pdf)

### After class

- Group presentation slides and annotated bibliography on _Data Management_ due upcoming week.

---

## Week 4: Data Management: Background and Purposes (group presentation) [_Back2Top_](#)

### Before class

- [Required readings](https://drive.google.com/drive/folders/1eziwxSu0agJfYjAcPu5VsNh5QxRFAFLj?usp=sharing)
  - CSSPrimer: Chapter 2.
  - Leonelli, Sabina. “Scientific Research and Big Data.” In The Stanford Encyclopedia of Philosophy, edited by Edward N. Zalta, Summer 2020. Metaphysics Research Lab, Stanford University, 2020. <https://plato.stanford.edu/archives/sum2020/entries/science-big-data/>.
  - Wickham, Hadley. “Tidy Data.” The Journal of Statistical Software 59, no. 10 (2014). <http://www.jstatsoft.org/v59/i10/>.
  - Goble, Carole, and David De Roure. “The Impact of Workflow Tools on Data-Centric Research.” In The Fourth Paradigm: Data-Intensive Scientific Discovery, edited by Tony Hey, Stewart Tansley, Kristin Tolle, and Jim Gray. Microsoft Research, 2009. <https://www.microsoft.com/en-us/research/publication/fourth-paradigm-data-intensive-scientific-discovery/>.
  - Fidler, Fiona, and John Wilcox. “Reproducibility of Scientific Results.” In The Stanford Encyclopedia of Philosophy, edited by Edward N. Zalta, Summer 2021. Metaphysics Research Lab, Stanford University, 2021. <https://plato.stanford.edu/archives/sum2021/entries/scientific-reproducibility/>.

### In class

- Student-lead group presentation and instructor lecture.
- Group discussion on annotated bibliography.
- Prepare Assignment 3: Gathering Literature in Your Field.

### After class

- Assignment 3: Gathering Literature in Your Field due upcoming week.
- Group presentation slides and annotated bibliography on _Concept Representation_ due in two weeks.

---

## Week 5: Data Management Exercise: Gathering Literature in Your Field [_Back2Top_](#)

### Before class

- Complete the Assignment and submit to OSF.

### In class

- Presentation and discussion of Assignment.
- Review peer assignments and provide feedback.
- Preview next exercise.

### After class

- Revise assignments according to feedback.
- Group presentation slides and annotated bibliography on _Concept Representation_ due in upcoming week.
  - Read required readings.
  - Prepare group presentation.
  - Write annotated bibliography.

---

## Week 6: Concept Representation: Background and Purposes (group presentation) [_Back2Top_](#)

### Before class

- [Required readings](https://drive.google.com/drive/folders/1eziwxSu0agJfYjAcPu5VsNh5QxRFAFLj?usp=sharing)
  - Creswell, John W. “The Selection of a Research Approach.” In Research Design: Qualitative, Quantitative, and Mixed Methods Approaches, 4th ed. Thousand Oaks: SAGE Publications, 2014.
  - Ragin, Charles C., and Lisa M. Amoroso. “The Goals of Social Research.” In Constructing Social Research: The Unity and Diversity of Method, 135–62. Pine Forge Press, 2011.
  - Grimmer, Justin, and Brandon M. Stewart. “Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts.” Political Analysis 21, no. 3 (2013): 267–97. <https://doi.org/10.1093/pan/mps028>.

### In class

- Student-lead group presentation and instructor lecture.
- Discussion on annotated bibliography.
- Preview Assignment 4: Automated Coding.
- Guest speaker: [Dr. Hanjin Mao](https://www.uhd.edu/faculty/maoh.aspx), Technologies in nonprofits.

### After class

- Review Assignment 4 (Automated Coding).

---

## Week 7: Concept Representation: Methods and tools [_Back2Top_](#)

### Before class

- Review Assignment 4 (Automated Coding).

### In class

- Inductive coding with topic modeling:
  - [Top2Vec](https://top2vec.readthedocs.io/en/latest/index.html)
  - [BERTopic](https://maartengr.github.io/BERTopic/index.html)
- Deductive coding (text classification):
  - [Fine-tune model with training dataset.](https://huggingface.co/docs/transformers/en/tasks/sequence_classification)
  - Prompt-based classification with LLMs: [OpenAI API](https://platform.openai.com/docs/api-reference/chat), [Models (Ollama service)](https://ollama.com/search), [deploy local LLM and API (liteLLM + Ollama)](https://docs.litellm.ai/docs/providers/ollama).
- Prepare Assignment 4: Automated Coding.

### After class

- Group presentation slides and annotated bibliography on _Data Analysis_ due soon.
- Prepare a draft submission of Assignment 4 (Automated Coding) for presenting in class.

---

## Week 8: Concept Representation Exercise: Automated Coding [_Back2Top_](#)

### Before class

- Prepare a draft submission of Assignment 4 (Automated Coding) for presenting in class.

### In class

- Presentation and discussion of Assignment.
- Review peer assignments and provide feedback.
- Prepare Assignment 4 (Automated Coding).

### After class

- Revise Assignment 4 according to feedback and submit.
- Group presentation slides and annotated bibliography on _Data Analysis_ due soon for upcoming session.
  - Read required readings.
  - Prepare group presentation.
  - Write annotated bibliography.

---

## Week 9: Data Analysis: Background and Purposes (group presentation) [_Back2Top_](#)

### Before class

- [Required readings](https://drive.google.com/drive/folders/1eziwxSu0agJfYjAcPu5VsNh5QxRFAFLj?usp=sharing)
  - Hofman, Jake M., Duncan J. Watts, Susan Athey, Filiz Garip, Thomas L. Griffiths, Jon Kleinberg, Helen Margetts, et al. “Integrating Explanation and Prediction in Computational Social Science.” Nature 595, no. 7866 (July 2021): 181–88. <https://doi.org/10.1038/s41586-021-03659-0>.
  - Ludwig, Jens, and Sendhil Mullainathan. “Machine Learning as a Tool for Hypothesis Generation.” Working Paper. Working Paper Series. National Bureau of Economic Research, March 2023. <https://doi.org/10.3386/w31017>.

### In class

- Student-lead group presentation and instructor lecture.
- Discussion on annotated bibliography.
- Review Assignment 5: Network Analysis.

### After class

- Review Assignment 5: Network Analysis.

---

## Week 10: Data Analysis: Methods and tools [_Back2Top_](#)

### Before class

- Review Assignment 5: Network Analysis.

### In class

TBD.

### After class

- Group presentation slides and annotated bibliography on _Scientific Communication_ due in two weeks.
- Prepare a draft submission of Assignment 5 (Network Analysis) for presenting in class.

---

## Week 11: Data Analysis Exercise: Network Analysis [_Back2Top_](#)

### Before class

- Prepare a draft submission of Assignment 5 (Network Analysis) for presenting in class.

### In class

- Presentation and discussion of Assignment.
- Review peer assignments and provide feedback.
- Prepare Assignment 5 (Network Analysis).

### After class

- Revise Assignment 5 according to feedback and submit.
- Group presentation slides and annotated bibliography on _Scientific Communication_ due in upcoming week.
  - Read required readings.
  - Prepare group presentation.
  - Write annotated bibliography.

---

## Week 12: Scientific Communication: Background and Purposes (group presentation) [_Back2Top_](#)

### Before class

- [Required readings](https://drive.google.com/drive/folders/1eziwxSu0agJfYjAcPu5VsNh5QxRFAFLj?usp=sharing)
  - Wickham, H. (2014). Tidy data. The Journal of Statistical Software, 59(10). <http://www.jstatsoft.org/v59/i10/>
  - Kirk, A. (2019). The Visualisation Design Process. In Data Visualisation: A Handbook for Data Driven Design (2nd edition, pp. 31–58). SAGE Publications Ltd.
  - Kirk, A. (2019). Working With Data. In Data Visualisation: A Handbook for Data Driven Design (2nd edition, pp. 95–117). SAGE Publications Ltd.

### In class

- Student-lead group presentation and instructor lecture.
- Discussion on annotated bibliography.
- Review [Data Dashboards](https://osf.io/cu7r3/) and [Final Project](/assets/css_final_template.pdf).

### After class

Prepare [Data Dashboards](https://osf.io/cu7r3/) or [Final Project](/assets/css_final_template.pdf).

<!-- 

---
### <a name="w3"> Week 3: Analyzing computational methods from a research design perspective </a>	[_Back2Top_](#)

### Before class
- Ragin, Charles C., and Lisa M. Amoroso. 2011. “What Is (and Is Not) Social Research?” In Constructing Social Research: The Unity and Diversity of Method, 5–32. Pine Forge Press.
- Ma, Ji, Islam Akef Ebeid, Arjen de Wit, Meiying Xu, Yongzheng Yang, René Bekkers, and Pamala Wiepking. 2021. “Computational Social Science for Nonprofit Studies: Developing a Toolbox and Knowledge Base for the Field.” VOLUNTAS: International Journal of Voluntary and Nonprofit Organizations, October. https://doi.org/10.1007/s11266-021-00414-x.

### In class
- Discussion and lecture on readings.
- Discussion on final project options.

---
### <a name="w4"> Week 4: Field visit: Texas Advanced Computing Center (TBD) </a>	[_Back2Top_](#)

### In class
- Visit TACC.
- Discussion on final project options.

### After class

- [<span style="color:red">**One-page research abstract [Research proposal] due this Friday**</span>](/assignments/#a4)

---
### <a name="w5"> Week 5: Computational methods: NLP algorithms and models as concept representation tools </a>	[_Back2Top_](#)

### Before class
- Required readings (copies of GRS chapters are on [course's Canvas site](https://utexas.instructure.com/courses/1360223/files/folder/w5) because of copyright)
	- Grimmer, Justin, Margaret E. Roberts, and Brandon M. Stewart. 2022. “Social Science Research and Text Analysis.” In Text as Data: A New Framework for Machine Learning and the Social Sciences. Princeton, New Jersey Oxford: Princeton University Press.
	- Grimmer, Justin, Margaret E. Roberts, and Brandon M. Stewart. 2022. “Principles of Measurement.” In Text as Data: A New Framework for Machine Learning and the Social Sciences. Princeton, New Jersey Oxford: Princeton University Press.
	- Jurafsky, Daniel, and James H. Martin. 2022. “Vector Semantics and Embeddings.” In Speech and Language Processing, 3rd draft. https://web.stanford.edu/~jurafsky/slp3/.
- Recommended readings:
	- Rodriguez, Pedro L., and Arthur Spirling. 2022. “Word Embeddings: What Works, What Doesn’t, and How to Tell the Difference for Applied Research.” The Journal of Politics 84 (1): 101–15. https://doi.org/10.1086/715162.
	- Grimmer, Justin, and Brandon M. Stewart. 2013. “Text as Data: The Promise and Pitfalls of Automatic Content Analysis Methods for Political Texts.” Political Analysis 21 (3): 267–97. https://doi.org/10.1093/pan/mps028.

### In class
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

### After class

Practice the coding sessions, play with your own datasets, revise research proposal.

---
### <a name="w6"> Week 6: Research design: Data management (student-lead) </a>	[_Back2Top_](#)

### Before class
- Recommended readings:
	- Baker, M. (2016). 1,500 scientists lift the lid on reproducibility. Nature News, 533(7604), 452. https://doi.org/10.1038/533452a
	- Wilson, Greg, D. A. Aruliah, C. Titus Brown, Neil P. Chue Hong, Matt Davis, Richard T. Guy, Steven H. D. Haddock, et al. 2014. “Best Practices for Scientific Computing.” PLOS Biology 12 (1): e1001745. https://doi.org/10.1371/journal.pbio.1001745.
	- Gentzkow, Matthew, and Jesse M. Shapiro. 2014. Code and Data for the Social Sciences: A Practitioner’s Guide. https://web.stanford.edu/~gentzkow/research/CodeAndData.pdf.
	- Wickham, Hadley. 2014. “Tidy Data.” The Journal of Statistical Software 59 (10). http://www.jstatsoft.org/v59/i10/.
	- Boyd, Nora Mills. 2018. “Evidence Enriched.” Philosophy of Science 85 (3): 403–21. https://doi.org/10.1086/697747.
	- Leonelli, Sabina. 2020. “Scientific Research and Big Data.” In The Stanford Encyclopedia of Philosophy, edited by Edward N. Zalta, Summer 2020. Metaphysics Research Lab, Stanford University. https://plato.stanford.edu/archives/sum2020/entries/science-big-data/.
- Empirical readings (TBD by student group)

### In class
- Discussion and lecture on readings.
- Discussion on final project.

### After class

Provide feedback to group report.

---
### <a name="w7"> Week 7: Computational methods: topic modeling and classification (instructor-lead) </a>	[_Back2Top_](#)

### Before class

No readings before class, practice the coding sessions from previous weeks, and **prepare a sample dataset of text for your proposed research** (we will need it in class for practice purposes).

### In class

- Overview: Technical background of topic modeling and classification, application in research
- Hands-on:
	- Topic modeling based on different vectorization methods: 
		- Static word embedding (universal-sentence-encoder-multilingual)
		- Contextual word embedding (BERT)
	- Generation of topic keywords
	- Classification of texts (code review)
	- Practice with your own datasets

### After class

Practice the coding sessions, play with your own datasets, revise research proposal.

---
### <a name="w8"> Week 8: Research design: Concept representation (student-lead) </a>	[_Back2Top_](#)

### In class
- Discussion and lecture on readings.
- Discussion on final project.

### After class

Provide feedback to group report.

---
### <a name="w9"> Week 9: Computational methods: Network analysis as a representation and analysis method (instructor-lead) </a>	[_Back2Top_](#)

### Before class
- Recommended readings:
	- Scott, John. 2017. “What Is Social Network Analysis?” In Social Network Analysis, Fourth edition. Thousand Oaks, CA: SAGE Publications Ltd.
	- Scott, John. 2017. “Terminology for Network Analysis.” In Social Network Analysis, Fourth edition, 73–94. Thousand Oaks, CA: SAGE Publications Ltd.
	- Watts, Duncan J. 2004. “The ‘New’ Science of Networks.” Annual Review of Sociology 30 (1): 243–70. https://doi.org/10.1146/annurev.soc.30.020404.104342.

### In class
- Discussion and lecture on readings.
- Discussion on final project.

### After class

Provide feedback to group report.

---
### <a name="w10"> Week 10: Research design: Data analysis (student-lead) (TBD) </a>	[_Back2Top_](#)

### Before class
- Recommended readings:
	- Hofman, Jake M., Duncan J. Watts, Susan Athey, Filiz Garip, Thomas L. Griffiths, Jon Kleinberg, Helen Margetts, et al. 2021. “Integrating Explanation and Prediction in Computational Social Science.” Nature 595 (7866): 181–88. https://doi.org/10.1038/s41586-021-03659-0.
	- Gerring, J. (2012). Mere Description. British Journal of Political Science, 42(4), 721–746. https://doi.org/10.1017/S0007123412000130
	- Humphreys, P. (2009). The philosophical novelty of computer simulation methods. Synthese, 169(3), 615–626. https://doi.org/10.1007/s11229-008-9435-2
- Empirical readings (TBD by student group)

### In class
- Discussion and lecture on readings.
- Discussion on final project.

### After class

Provide feedback to group report.

---
### <a name="w11"> Week 11: Computational methods: Process of network analysis</a>	[_Back2Top_](#)

### Before class
- Recommended readings:
	- Borgatti, Stephen P., and Daniel S. Halgin. 2011. “On Network Theory.” Organization Science 22 (5): 1168–81. https://doi.org/10.1287/orsc.1100.0641.
	- [Review network analysis algorithms](https://networkx.org/documentation/stable/reference/algorithms/index.html#)

### In class
- Discussion and lecture on readings.
- Discussion on final project.

### After class

Work on final project, prepare to finalize the written report for [Assignment 3: Student-lead seminar on research design](https://css.jima.me/assignments/#a3)

---
### <a name="w13"> Week 13: Research design: Scientific communication (student-lead) (TBD) </a>	[_Back2Top_](#)

### Before class

- Recommended readings:
	- Wickham, H. (2014). Tidy data. The Journal of Statistical Software, 59(10). http://www.jstatsoft.org/v59/i10/
	- Kirk, Andy. 2019. Data Visualisation: A Handbook for Data Driven Design. 2nd edition. S.l.: SAGE Publications Ltd.
	- "Data storytelling" books through [university library](https://search.lib.utexas.edu/discovery/search?query=any,contains,data%20storytelling&tab=LibraryCatalog&search_scope=MyInstitution&vid=01UTAU_INST:SEARCH&offset=0). The issue is that there are too many such books, and not all of them are helpful. [This book](https://search.lib.utexas.edu/permalink/01UTAU_INST/9e1640/alma991058188717506011) is a bestseller on Amazon.

- Recommended DataCamp modules:
	- [Understanding Data Visualization](https://app.datacamp.com/learn/courses/data-visualization-for-everyone)
	- [Data Storytelling Concepts](https://app.datacamp.com/learn/courses/data-storytelling-concepts)
	- [Data Communication Concepts](https://app.datacamp.com/learn/courses/data-communication-concepts)

- Empirical readings (TBD by student group)

### In class
- Discussion and lecture on readings.
- Discussion on final project.

### After class

Provide feedback to group report. 

-->

<!-- 
---
### <a name="w2"> Week 2: Data management and documentation </a>	[_Back2Top_](#)

### Before class
- Readings:
	- GS: All chapters excluding "Automation."
	- Wilson, Greg, Jennifer Bryan, Karen Cranston, Justin Kitzes, Lex Nederbragt, and Tracy K. Teal. 2017. “Good Enough Practices in Scientific Computing.” PLOS Computational Biology 13 (6): e1005510. https://doi.org/10.1371/journal.pcbi.1005510.

### In class
- Discussion and lecture on readings.

### After class
- [<span style="color:red">**Assignment 2 due this week's Sunday.**</span>](/open_data/assignments/#a2)

---
### <a name="w3"> Week 3: Efficient algorithm and automated workflow </a>	[_Back2Top_](#)

### Before class
- Readings:
	- Bird, Steven, Ewan Klein, and Edward Loper. 2009. “Writing Structured Programs.” In Natural Language Processing with Python. Beijing ; Cambridge [Mass.]: O’Reilly.
	- GS: Automation.

### In class
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

### After class
- Recommended course: [Python Data Science Toolbox (Part 1)](https://www.datacamp.com/courses/python-data-science-toolbox-part-1) (3 hours)

 -->