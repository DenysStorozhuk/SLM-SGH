# SLM Spring 2022/23

###### This SGH-SLM repository contains files and codes used in SLM labs and lectures taught and published by Professors Bogumił Kamiński, Łukasz Kraiński, Bartosz Pankratz, Daniel Kaszyński, Mateusz Zawisza. In addition to serving as a personal notepad to enhance my understanding, this repository also includes some of the homework and additional work I have completed for in-depth analysis. It provides a glimpse into the efforts I have made to delve deeper into the subject matter.


**Required software**

During the course we'll use Jupyter Notebook with Julia. 
To run the code provided during classes you'll need:
* [Julia](https://julialang.org/downloads/)
* [Jupyter](https://jupyter.org/install) Notebook or Jupyter Lab
* [Git](https://git-scm.com/)

---
**Preparing working environment**

Make sure you have [Julia](https://julialang.org/downloads/) installed.
The course was prepared under Julia 1.8.2.

1. Clone the repository to a local folder on your computer:
```shell
git clone https://github.com/KrainskiL/SLM_S2023.git
```
2. Start Julia in your local folder:
```shell
cd SLM_S2023
julia --project
```
3. Run the following commands in the Julia REPL:
```julia
using Pkg
Pkg.instantiate()
Pkg.status()
```
4. Start Jupyter Notebook with:
```julia
using IJulia
notebook(dir=pwd())
```

---
**Contact**

Name: Łukasz Kraiński

Email: lkrain@sgh.waw.pl

Consultations: 08:00 - 9:40 G-116 Thursdays

---
**Lecturers**

* lecturer: Bogumił Kamiński
* laboratories: Łukasz Kraiński

---
**Schedule**

* lectures: Mondays, 9:50-11:30, Aula III
* laboratories: Thursdays, according to laboratory group, G-116

---
**Lectures**

|     Date          |     Subject                                                                      |
|-------------------|----------------------------------------------------------------------------------|
|     2023-02-20    |     Introduction to statistical learning                                       |
|     2023-02-27   |     Managing analytical project using git and GitHub                           |
|     2023-03-06   |     Methods of evaluation of classifiers                                         |
|     2023-03-13   |     Regularizationin machine learning                                                |
|     2023-03-20    |     Nonparametric models                                                         |
|     2023-03-27   |     Generative models (Ł. Kraiński)                             |
|     2023-04-03   |     Introduction to Julia language                                                    |
|     2023-04-17    |     Dimensionality reduction methods   |
|     2023-04-24   |     Working with text data                                                         |
|     2023-05-08   |     Conformal prediction (M. Zawisza)                                        |
|     2023-05-15   |     Working with data using HTTP APIs                               |
|    2023-05-22    |     Trustworthy AI (D. Kaszyński)                                                     |
|     2023-05-29  |     Analyzing graph data                                            |
|     2023-06-05    |     Course summary and theoreticalexamination                                                |

---
**Laboratories**
|     #                    |     Subject                                                                                    |
|--------------------------|------------------------------------------------------------------------------------------------|
|     1                    |     Introduction to Jupyter Notebooks, Machine Learning and data retrieval in Julia   |
|     2                    |     Evaluation and assessment of classification models                                                    |
|     3                    |     Hyperparameter tuning and cross-validation                                                           |
|     4                    |     Interpretable Machine Learning                                        |
|     5                    |     Model deployment                                                                     |
|     6                    |     Modelling competition                                                                    |
|     7   |     Practical examination                                        |

---
**Literature**

Materials shared during the class

Kamiński  B.(2022),  [Julia  for Data Analysis](https://www.manning.com/books/julia-for-data-analysis)

Mykel  J.  Kochenderfer,  Tim  A.  Wheeler,  And  Kyle  H.  Wray  (2022),  [Algorithms  for  Decision Making](https://algorithmsbook.com/)

Stephen    Boyd    and    Lieven    Vandenberghe, [Introduction    to Applied    Linear    Algebra](http://vmls-book.stanford.edu/)

Gareth  J.,  Witten  D.,  Hastie  T.,  Tibshirani  R.  (2021),  [An  Introduction  to  Statistical  Learning with Applications in R](https://web.stanford.edu/~hastie/ISLR2/ISLRv2_website.pdf)

Hastie T., Tibshirani R., Friedman J. (2017), [The Elements of Statistical Learning](http://www-stat.stanford.edu/~tibs/ElemStatLearn/)

William E. Shotts (2019), [Linux Command Line](https://linuxcommand.org/lc3_learning_the_shell.php)

---
**Course evaluation criteria**

* Theoretical examination on last lecture (50 points)
* Practical test on last laboratory (50 points)
    * Test is conducted during the last laboratory. The time to complete the test is 90 minutes. Test file (Jupyter notebook containing set of tasks) will be shared through MS Teams group just before the class. The test is conducted in Julia language and all types of didactic materials can be used during evaluation (notes, documentation, notebooks from the course, etc.). The test is an individual evaluation, hence communication with other students during the test is prohibited. Filled notebook should be sent to lkrain@sgh.waw.pl before the end of the class - please put your index number in the title of the notebook file. Test results will be shared through MS Teams.

* Extra points:
    * Homework
    * Laboratory competition
    * Completion of course: https://juliaacademy.com/p/introduction-to-dataframes-jl1 (5 points)


---
**Grading rules**
|From |To|Final grade|
|-----|--|--------|
|0 |49| 2.0|
|50 |59 |3.0|
|60 |69 |3.5|
|70 |79 |4.0|
|80 |89 |4.5|
|90 |100 |5.0|

---

*Preparation of the educational materials has been supported by the Polish National Agency for Academic Exchange under the Strategic Partnerships programme, grant number BPI/PST/2021/1/00069/U/00001.*

![SGH & NAWA](logo.png)
