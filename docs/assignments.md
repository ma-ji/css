# Assignments (TBD)
---

<!-- %%%%%%Open source community / pedagogy as an assignment%%%%%-->

- [Assignment 1: Plagiarism test (individual, 5 points)](#a1)
- [Assignment 2: Create your own cloud computing server (individual, 5 points)](#a3)
- [Assignment 3: Student-lead seminar on research design (group, 20 points)](#a4)
- [Assignment 4: Research proposal (group or individual, 30 points)](#a5)
- [Assignment 5: Final project (group or individual, 40 points)](/final)

<!-- - [Assignment 2: Documentation (individual, 5% points)](#a2)
- [Assignment 4: Parallel computing (individual, 5% points)](#a4)
- [Assignment 5: Disambiguation using algorithm (individual/group, 15% points)](#a5)
- [Assignment 6: NLP/Network analysis (individual/group, 15% points)](#a6)
- [Assignment 7: Analysis and presentation of empirical paper(s) (individual, 15% points)](#a7)
- [Assignment 8: Final project (individual/group, 35% points)](/final) -->

Late submissions are not accepted. Check due dates on Canvas.

---
### <a name="a1"> Assignment 1: Plagiarisms test (individual, 5% points) </a>

The first assignment of this course is to [pass the plagiarism test and obtain a certificate at the master and doctoral level](https://plagiarism.iu.edu/index.html). Plagiarism is a serious academic misconduct. You will receive zero grade on plagiarized work and there may be other consequences. We have been told not to do this maybe since primary school, and we are always assuming we know what plagiarism is. However, we may assume we know too much (e.g., [famous cases of plagiarism](https://www.google.com/search?q=famous+cases+of+plagiarism)).

You do not need to take this test if you have a comparable certification or you took this test before, but the validity of your certification needs to be approved by the instructor.

"All assignments in this course may be processed by TurnItIn, a tool that compares submitted material to an archived database of published work to check for potential plagiarism. Other methods may also be used to determine if a paper is the student's original work. Regardless of the results of any TurnItIn submission, the faculty member will make the final determination as to whether or not a paper has been plagiarized" (Statement from the _Faculty Writing Committee: Guidelines for Preventing Plagiarism_).

For this assignment, please submit your certificate as a file to [Canvas](/#).


---
### <a name="a2"> Assignment 2: Documentation (individual, 5% points) </a>

TBD.

---
### <a name="a2"> Assignment 2: Create your own cloud computing server (individual, 5% points) </a>

Tasks:
1. Create a 48-core VM on [ChameleonCloud](https://chameleoncloud.readthedocs.io/en/latest/getting-started/index.html);
2. Install [Anaconda Python](https://www.anaconda.com/distribution/);
3. Run a [Jupyter Notebook](https://jupyter-notebook.readthedocs.io/en/stable/public_server.html) server with password and SSL for encrypted communication;
4. Login your Jupyter Notebook server through web-browser;
5. [Save an image of your instance](https://chameleoncloud.readthedocs.io/en/latest/technical/images.html), submit screenshots through Canvas showing: 1) instance image is saved successfully, and 2) Jupyter server is started successfully;
6. After submission, release your IP and server to other users (if you don't plan to use the instance).

** _Special attention: ChameleonCloud often has technical glitches, so please DON'T procrastinate this assignment to the last minute. If you have technical issue, submit a ticket through [Help Desk](https://www.chameleoncloud.org/user/help/). They almost only work on weekdays and will reply you in one or two business days. Again, don't procrastinate this assignment._ **

Knowledge and skills practiced:
- Using cloud computing platform;
- Using command line terminal and Linux system.

---
### <a name="a3"> Assignment 3: Parallel computing (individual, 5% points) </a>

Tasks:
1. Start a Jupyter server as you did in Assignment#2;
2. Install [`htop`](https://hisham.hm/htop/);
3. Define a function to clean, process, or analyze a large dataset of your interest;
4. Compare the efficiency of serial computing to that of parallel computing;
5. Submit a screenshot of `htop` showing all cores are crunching numbers.

Knowledge and skills practiced:
- Using cloud computing platform;
- Using command line terminal and Linux system;
- Python programming: parallel computing.

---
### <a name="a4"> Assignment 4: Disambiguation using algorithm (individual/group, 15% points) </a>

Disambiguating entity is a common task in data preprocessing. For example, the University of Texas at Austin can be written as "UT Austin," "UT-Austin," or even "UTA." How can we recognize these records and give them a unique ID? This assignment will practice this ability.

Tasks:
[The dataset](https://utexas.instructure.com/files/50261524/download?download_frd=1) provided to you is retrieved from [Scopus](https://dev.elsevier.com/index.html), one of the largest bibliographical databases in the world. Each line is a record of a published paper on civil society studies. You are expected to:
1. Generate a codebook of this dataset;
2. Create criteria for disambiguating authors and affiliations.
3. Explain why the criteria can generate valid results.
4. Compile a function according to the criteria, run the function on records, and give unique IDs to these entities.
5. Verify accuracy: choose a random sample and manually check the false positive and false negative rates.
6. Describe: 1) who are the most productive authors in civil society studies? 2) Which are the most productive institutions in civil society studies? 3) How you define "productive."
7. Remember to document everything.

---
### <a name="a5"> Assignment 5: NLP/Network analysis (individual/group, 15% points) </a>

TBD.

<!-- Review the dataset for Assignment 4, prepare two sets of questions:

- Descriptive. For example, who is the most connected scholar/institution?
- Inferential. For example, are scholars from wealthier countries/institutions more likely to be “structural holes”?

After instructor's approval, these will be the questions you need to answer as Assignment 5. You are expected to submit a detailed report.
 -->

---
### <a name="a6"> Assignment 6: Analysis and presentation of empirical paper(s) (individual, 15% points) </a>

Analyze and present empirical paper(s) using computational social science methods. TBD.
