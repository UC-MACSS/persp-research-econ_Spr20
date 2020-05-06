# MACS 30250 - Perspectives on Computational Research in Economics (Spring 2020)

|  | [Dr. Richard Evans](https://sites.google.com/site/rickecon/) |
|--------------|--------------------------------------------------|
| Email | rwevans@uchicago.edu |
| Office | 1155 E 60th St, Room 217 (but really in Utah) |
| Office Hours | M 3:00-5:00pm |
| GitHub | [rickecon](https://github.com/rickecon) |

* **Meeting day/time**: MW 1:30-2:50pm Central Time (Chicago), Remote access
* Office hours also available by appointment

## Course description

This course focuses on applying computational methods to conducting social scientific research in economics through a student-developed research project. Students will identify a research question of their own interest that involves a direct reference to economic theory, use of data, and a significant computational component. The students will collect data, develop, apply, and interpret statistical learning models, and generate a fully reproducible research paper. We will identify how computational methods can be used throughout the research process, from data collection and tidying, to exploration, visualization and modeling, to the final communication of results. The course will include modules on theoretical and practical considerations, including topics such as epistemological questions about research design, writing and critiquing papers, and additional computational tools for analysis.

## Grades

|     Assignment              | Points | Quantity | Total points | Percent |
|-----------------------------|--------|----------|--------------|---------|
| Proposal                    |    10  |      1   |        10    |   6.2%  |
| Literature review           |    15  |      1   |        15    |   9.4%  |
| Methods/initial results     |    15  |      1   |        15    |   9.4%  |
| Peer evaluations of posters |     2  |      5   |        10    |   6.2%  |
| Poster presentation         |    30  |      1   |        30    |  18.8%  |
| Final paper                 |    40  |      1   |        40    |  25.0%  |
| Problem sets                |    10  |      4   |        40    |  25.0%  |
| **Total Points**            |        |          |       160    | 100.0%  |

Students will turn assignments in via their own public GitHub fork of the main class repository (e.g., `https://github.com/YourGitHubHandle/persp-research-econ_Spr20`). The directory structure of this repository should be the following.

* `github.com/YourGithubHandle/persp-research-econ_Spr20/`
  * Assignments
    * PS1
    * PS2
    * PS3
    * PS4
  * Proposal
  * LitReview
  * MethodsResults
  * Poster
  * FinalPaper


## Late Problem Sets

Late problem sets will be penalized 2 points for every hour they are late. For example, if an assignment is due on Monday at 1:30pm Central Time (Chicago), the following points will be deducted based on the time stamp of the last commit.

| Example PR last commit | points deducted |
| ---------------------- | --------------- |
| 1:31pm to 2:30pm       | -2 points       |
| 2:31pm to 3:30pm       | -4 points       |
| 3:31pm to 4:30pm       | -6 points       |
| 4:31pm to 5:30pm       | -8 points       |
| 5:31pm and beyond      | -10 points (no credit) |


## Disability services

If you need any special accommodations, please provide us with a copy of your Accommodation Determination Letter (provided to you by the Student Disability Services office) as soon as possible so that you may discuss with me how your accommodations may be implemented in this course.


## Course schedule

| Date | Day | Topic | Reading | Recording | Assignment |
|------|-----|-------|---------|-----------|------------|
| Apr  6 | M | Overview/reproducibility in science | [Slides](Slides/Reprod_slides.pdf) | [Video](https://uchicago.zoom.us/rec/play/upUudeuhqDo3S4DHtwSDBfR-W43pLais2yAa_vIEyBnjAndWOgb0NbJDMOFDTfeWkWx0qMBVcgqHTPt0) |  |
| Apr  8 | W | Abstract/intro/conclusion | [Slides](Slides/IntroAbsConcl_slides.pdf) |  |  |
| Apr 13 | M | Theory section of paper | [Slides](Slides/TheorySection_slides.pdf) | [Video](https://uchicago.zoom.us/rec/play/7J0rduD7-G43HYWd5ASDUaAoW9W_Laus0nAb-fUExUvnACMKMwGvN-MRZbeC65lh9TikRbqpQgtbBP9r) |  |
| Apr 14 | Tu |  |  |  | [Proposal slides due](Assignments/project-proposal.md) |
| Apr 15 | W | Proposal presentations |  | [Video](https://uchicago.zoom.us/rec/play/6JIsf7v6r2o3SdfE5ASDAfZ_W9W6Lqis0nUb-aUMzB7hU3gEZgekNbcRYLc5y8PA3qK4879I40KTfZ5J) | [Proposal presentations](Proposal/README.md) |
| Apr 20 | M | Data section of paper | [Slides](Slides/DataSection_slides.pdf) | [Video](https://uchicago.zoom.us/rec/play/vZUvd-D7_G83TtzHtgSDV6B5W9W9faqs0ncc-vsKxBzmViMDN1unZrJHY-JnJyFfRYSO-LecQicjEZ1d) |  |
| Apr 22 | W | Computational results section of paper | [Slides](Slides/ResultsSection_slides.pdf) | [Video](https://uchicago.zoom.us/rec/play/u5Qkdrv9rG03H4WQtgSDC_J6W464Kqys2ycY-qEFxB2xUXgHZ1KkZOMTYLGQjtfXWlmb-_Gd7nJf9Dtw) |  |
| Apr 27 | M | Kernel density estimation | [Notebk1](https://github.com/UC-MACSS/persp-research-econ_Spr20/blob/master/Notebooks/KDE/05.13-Kernel-Density-Estimation.ipynb) | [Video](https://uchicago.zoom.us/rec/play/vMJ5dur5pjw3TtaXsgSDBv8rW46-eqmshncWr_dYmU-0UnJSMQfybrdEZLEqA35UzvXawvFOC0Gp6hus) | [PS1](ProblemSets/PS1/PS1.pdf) |
| Apr 29 | W | Kernel density estimation | [Notebk2](https://github.com/UC-MACSS/persp-research-econ_Spr20/blob/master/Notebooks/KDE/KDE.ipynb) | [Video](https://uchicago.zoom.us/rec/play/uJF-d7irqjs3SIbG4QSDAfRwW47rLKysgSNIrvEInh62AXBSZgDwYOQaNuW0QRndAxFybEP5-xGLuRAB) | [Lit review section due](Assignments/lit-review.md) |
| May  4 | M | Parallel computing | [Notebk](Notebooks/Parallel/parallel.ipynb) | [Video](https://uchicago.zoom.us/rec/play/7pYpdeqr-mk3GNfBtASDAqN9W9Treq6s0iUZ_PsMzRnmB3RWZFevYLAXZrR6ESf27shDOt2sgDgv79os) | [PS2](ProblemSets/PS2/PS2.pdf) |
| May  6 | W | Parallel computing | [Dask Tutorial](https://github.com/dask/dask-tutorial) | [Video](https://uchicago.zoom.us/rec/play/uMV5Iemvqj43TN2csgSDB6UvW9TpfKus1XMf86UNnUm0UHQEY1OhN-cRM7GyoJX_g3ZOU81q3qB8X6EI) |  |
| May 11 | M | Workshop papers/office visits | [Schedule](OfficeVisits/README.md) |  |  |
| May 13 | W | Dynamic programming with interpolation | Notebk | Join Zoom | PS3 |
| May 18 | M | Dynamic programming with interpolation |  | Join Zoom |  |
| May 20 | W | Workshop papers/office visits | Schedule |  |
| May 25 | M | **No class (Memorial Day Holiday)** |  |  |
| May 27 | W | Effective presentations, poster, slides | Slides/Notes | Join Zoom | [Methods/initial results section due](Assignments/methods-results.md) |
| Jun  1 | M | Overlapping generations models | Notes | Join Zoom | PS4 |
| Jun  3 | W | Overlapping generations models |       | Join Zoom | [Poster due](Assignments/poster.md) |
| Jun 4-5 | Th-Fri | Zoom poster presentations |  | Join Zoom |  |
| Jun  10 | W | Final papers due at 11:59pm |  |  | [Papers due](Assignments/final-paper.md) |


## References and Readings

* Casadevall, Arturo and Ferric C. Fang, "[Reproducible Science](https://iai.asm.org/content/78/12/4972)," *American Society for Microbiology: Infection and Immunity*, 78:12, pp. 4972-4975 (2010).
* Christensen, Garret S. and Edward Miguel, "[Transparency, Reproducibility, and the Credibility of Economics Research](https://www.aeaweb.org/articles?id=10.1257/jel.20171350)," *Journal of Economic Literature*, 56:3 pp. 920-980 (Sep. 2018).
* Evans, Richard W., "[Public Debt, Interest Rates, and Negative Shocks](https://sites.google.com/site/rickecon/Evans2020.pdf?attredirects=0)," *American Economic Review* (forthcoming, May 2020).
* Ince, Darrel C., Leslie Hatton, and John Graham-Cumming, "[The Case for Open Computer Programs](https://www.nature.com/articles/nature10836)," *Nature*, 482, pp. 485-488 (23 Feb. 2012).
* Miguel, E., C. Camerer, K. Casey, J. Cohen, K. M. Esterling, A. Gerber, R. Glennerster, D. P. Green, M. Humphreys, G. Imbens, D. Laitin, T. Madon, L. Nelson, B. A. Nosek, M. Petersen, R. Sedlmayr, J. P. Simmons, U. Simonsohn, and M. Van der Laan, "[Promoting Transparency in Social Science Research](http://science.sciencemag.org/content/343/6166/30)," *Science* (3 Jan. 2014).
* Niemeyer, Kyle, "[*Nature* Editorial: If you want reproducible science, the software needs to be open source](https://arstechnica.com/science/2012/02/science-code-should-be-open-source-according-to-editorial/)," *Ars Technica* (26 Feb. 2012).
