# Course Schedule
---

[Reading Materials by Week](https://utexas.instructure.com/courses/1261330/files)

- [Week 0 Pre-course](#w0)

### Computational methods and research design fundamentals (3 weeks)

- [Week 1: Course introduction](#w1)
	- Key points: course structure, assignments, syllabus
- [Week 2: Data management and documentation](#w2)
	- Key points: workflow, version control
- [Week 3: Efficient algorithm and automated workflow](#w3)
	- Key points: algorithm optimization, iteration, automation
- Week 4: Data reduction, validation, and robustness (TBD)
- Week 5: no class; week for assignments; group meeting with instructor.

### Student-lead seminar (2 weeks)

- Week 6: Presentation of empirical studies (2 groups)
- Week 7: Presentation of empirical studies (2 groups)

### Instructor-lead sessions: Choose from [these options](/voted_options) (3 weeks)

- Week 8: Voted module 1
- Week 9: Voted module 2
- Week 10: Voted module 3
- Week 11: no class; week for assignments; group meeting with instructor.

### Student-lead sessions: Decided before Week 8 (3 weeks)

- Week 12: Student-lead module 1
- Week 13: Student-lead module 2
- Week 14: Student-lead module 3

### Final project
- Week 15: Final project

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



