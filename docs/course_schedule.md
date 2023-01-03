# Course Schedule
---

[Reading Materials by Week](https://utexas.instructure.com/courses/1261330/files)

<!-- - [Week 0 Pre-course](#w0) -->

### Computational methods and research design fundamentals (4 weeks)

- [Week 1: Course introduction](#w1)
	- Key points: course structure, assignments, syllabus
- [Week 2: Computational methods for social sciences: Overview](#w2)
	- Key points: philosophical and epistemological fundamentals, research design overview, comparison between CSS and conventional approaches
- Week 3: Analyzing computational methods from a research design perspective
	- Key points: data management, concept representation, data analysis, and visualization
- Week 4: Field visit: Texas Advanced Computing Center
	- Visit TACC; Discussion on [final project options](/final/)

<!-- 
- [Week 3: Efficient algorithm, data management and documentation, automated workflow](#w3)
	- Key points: algorithm optimization, iteration, automation, workflow, version control
- Week 4: Data reduction, validation, and robustness (TBD)
 -->

### Analyzing computational social science methods (8 + 1 weeks)

Instructor-lead sessions are voted by the class from [these options](/voted_options)

- Week 5: Instructor-lead seminar on computational methods: Voted module 1
- Week 6: Student-lead seminar on research design: Data management
- Week 7: Instructor-lead seminar on computational methods: Voted module 2
- Week 8: Student-lead seminar on research design: Concept representation
- Week 9: Instructor-lead seminar on computational methods: Voted module 3
- Week 10: Student-lead seminar on research design: Data analysis
- Week 11: Instructor-lead seminar on computational methods: Voted module 4
- _<u>Week 12: Group consultation on final project (no class)</u>_
- Week 13: Student-lead seminar on research design: Visualization

### Final project
- Week 14: Final project presentations

---
# Weekly Details (TBD)
---

<!-- ### <a name="w0"> Week 0 Pre-course </a>	[_Back2Top_](#) -->


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
- Register Accounts:
	- [GitHub](https://github.com/) / [Free GitHub Pro (GitHub Education)](https://education.github.com/students)
	- [Chameleon Cloud](https://www.chameleoncloud.org/)

### After class
- [Review "Getting started with Chameleon Cloud"](https://chameleoncloud.readthedocs.io/en/latest/getting-started/index.html)

---
### <a name="w2"> Week 2: Computational methods for social sciences: Overview </a>	[_Back2Top_](#)

#### Before class
- Readings (TBD)

### In class
- Discussion and lecture on readings.
- Hands-on: High-performance cloud computing with [Chameleon](https://www.chameleoncloud.org/)
- Discussion on final project options.

### After class
- [<span style="color:red">**Assignment 1 due this Friday**</span>](/assignments/#a1)


<!-- 
---
### <a name="w2"> Week 2: Data management and documentation </a>	[_Back2Top_](#)

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