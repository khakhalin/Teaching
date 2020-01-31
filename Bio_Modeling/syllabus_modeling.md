# Computational Biology

*Version: Jan 2020*

## General info

- **Instructor:** Arseny Khakhalin; [khakhalin@bard.edu](mailto:khakhalin@bard.edu) 
- **Class meetings**: Mon & Wed, 8:30 - 11:30 am , RKC 200.
- **Drop-in hours** (aka "office hours"): tbc
   If you have a short question, you can also just stop by when the door is open.  And if you have a long question, send me an email, and we can schedule a meeting.

The main way of communication for this course is the [**Piazza** discussion board](https://piazza.com/). It's a sort of a dedicated forum created specifically for this course (a mix between facebook, reddit, quora, and stackexchange). By default it will send you email updates all the time, but you can tune these updates to your liking (receive them immediately / daily / weekly / never, etc).

* All announcements about the course will go on Piazza
* All materials for the course will be posted on Piazza.
* If you have general questions about the course, they should be asked on Piazza. For personal questions and updates, please either come to office hours, or use email
* Homework assignments will be collected on Piazza. Some homework will be post anonymously, some will be open (depending on the nature of the assignment: TBC).

Instructor will continue to improve this syllabus during the semester, to make the course even more amazing (for example, move topics around if we are slow, change reading materials, etc.)

# Course description

In this course, we will learn to model, visualize, and analyze biological processes. If you are a biologist, you will learn to code in Python (using Jupyter notebooks), which is an important, empowering, and highly marketable skill. Throughout the semester, you will be working on two long projects, gradually building up their complexity, and improving your code. If you are a computer scientist or a mathematician, you will learn how to apply your computing skills to the analysis of scientific problems; how to use models to make conceptual predictions about the world, and describe these predictions in academic writing. The course will lead to a 4-week long individual project. Prerequisites: either BIO202 (Ecology and Evolution), or CMSC 201 (Data structures), or permission from the instructor.

# Course Goals

By the end of this course you hopefully will:

* Be able to program in Python, including numpy, and matplotlib
* Develop some good healthy habits of computational work, including version control (git, GitHub), prototyping in Jupyter, using Markdown for documentation and journaling
* Become familiar with elements of complexity science, numerical integration, elements of dynamic systems theory, network science
* Know how to create computational models of real processes; parameterize these models, explore the parameters landscape, and make quantitative and qualitative predictions
* Get experience with writing up your modeling experiments.

# Course materials

* Introduction to Python:  https://greenteapress.com/wp/think-python-2e/
* Introduction to complexity:  https://greenteapress.com/wp/think-python-2e/
* Some basic info on population ecology: TBC
* Some basic info on dynamical systems: TBC
* Network Science: TBC. Possible books:
  * http://networksciencebook.com/chapter/1
  * http://www.cs.cornell.edu/home/kleinber/networks-book/

# Grading

This course is graded using a “Specification Grading” system, which is known to work better than the standard “Point-based” system, both in terms of final results, and student experience. The gist here is that each letter grade comes with a list of criteria, and it is up to you to pick the level you want to achieve.

To get a **C:** 

* Participate in 80% of classes
* Submit 70% of assignments. They don’t have to be perfect, but they need to be reasonable. If any given submission is problematic, I’ll let you know, so that you could improve next time.

To get a **B:**

* Participate in 90% of classes
* Submit 90% of assignments
* Present your project at the end of this class

To get an **A:**

* **On top of everything specified in “B”**, develop a unique project, present it in class, and write it up as a mini-paper. The project can either model something new (something we have not done in class), or take any problem we worked on, and add to it one more step, and one more question. You will need to OK your project with the instructor before you commit to it. It may be possible to do projects in groups of two students, but we'll need to discuss it all together in class at some point, and come up with a decision.

# Attendance

If you miss more than 6 classes, you will have to withdraw from the course. Please don't do it.

If you know in advance that you may have to miss a class, please let me (the instructor) know in advance!

# Academic integrity and plagiarism

For homework and in-class tests, the *writing* should be done by *you*. Borrowing texts from other people or from the Internet without an acknowledgement (such citation, reference, explicit acknowledgement) is unacceptable, and will result in bad things happening.

At the same time, for most assignments, collaboration and team work are heavily encouraged. Seek inspiration by talking to your peers before doing your work! Show your work to other people and ask for their suggestions and feedback! Offer your help to struggling compatriots! Except for quizzes and exams, I expect you to do your own work, but also productively collaborate, as it happens in real life.

# Snow policy

During heavy weather classes are tied to the activity of Bard shuttle. If the shuttle is canceled, the classes are also canceled. If shuttle service is restored, and we have time to react, the class is typically held. If there is a risk of shuttle cancellation, make sure to frequently check Piazza (or email as a back-up).

# Weekly Schedule

For the full list of readings, see The Appendix 1 below.

| Week | **Dates**  | Topic                                                        | Reading      |
| ---- | ---------- | ------------------------------------------------------------ | ------------ |
| 1    | Jan 27, 29 | Intro. Jupyther. Python basics (all but objects). Numpy, Matplotlib. Incremental development. GitKraken and GitHub. Simple models. | Think Python |
| 2    | Feb 3, 5   | Logistic growth. Numerical integration. Model parameters, qualitative answers. Chaos. Sensitivity to starting conditions. |              |
| 3    | 10, 12     | Predator-prey ODEs (Lotka–Volterra).                         |              |
| 4    | 17, 19     | Agents. Objects. Model for Mark-and-Recapture. Effects of geometry. |              |
| 5    | 24, 26     | Predator-prey agent-based. P(extinction). Cost of sexual reproduction. Parameter search (for most commotion): grid based or optimization. |              |
| 6    | Mar 2, 4   | Allele frequency, gene drift (P allele extinction). Effects of sexual reproduction. |              |
| 7    | 9, 11      | Selection, and effects of sexual reproduction on allele diversity. Effects of preferential mating. |              |
| 8    | 16, 18     | TBC: speciation? Genetic algorithms? Come up with a new small project together, as a group? |              |
| 9    | 23, 25     | SPRING BREAK, no classes                                     |              |
| 10   | 30, Apr 1  | Network construction and analysis. Random, preferential attachment, small world, degree distribution, centrality. |              |
| 11   | 6, 8       | Pandemics on a network. Herd immunity.                       |              |
| 12   | 13, 15     | Effects of assortative friendship. Strategic vaccination.    |              |
| 13   | 20, 22     | tbc                                                          |              |
| 14   | 29         | No class on 27 (Advising day). 29 is a sproj day. Declare projects (peer-review)? |              |
| 15   | 4, 6       | No classes (Biology Boards Week)                             |              |
| 16   | 11, 13     | Project Presentations (Completion week officially starts 13) |              |

Ideas for events and assignments that may or may not happen:

* A week when we come up with a model idea all together as a group?

Sample ideas for personal projects:

* Effects of habitat fragmentation
* 3-species situation (cabbage, rabbits, foxes)
* Effects of seeking or avoidance behavior in agents
* Analysis of spatial and temporal waves in population models
* Evolutionary algorithm or direct optimization for some parameters

# Appendix 1. Readings

Week 1. Intro

* Think Python: https://greenteapress.com/wp/think-python-2e/
  First 3 chapters: Program, Variables, Functions

Week 2. Logistic growth. Numerical integration. Model parameters, qualitative answers. Chaos. Sensitivity to starting conditions.

* Something numerical integration
* Think Python, chapters on Conditionals and recursion; Fruitful functions; Iteration

Week 3. Predator-prey ODEs (Lotka–Volterra)

* Think Python, chapters on Strings (just in case), Lists, Dictionaries, Tuples

Week 4. Agents. Objects. Model for the Mark-and-Recapture procedure. Effects of enclosure geometry.

* Introduction to the philosophy of agent modeling (TBC, not vetoed yet): http://epubs.surrey.ac.uk/1580/1/fulltext.pdf
* Think Python, chapters on Classes and objects, Classes and functions, Classes and methods. The rest of the book (3 more chapters) are optinal, but nice to have.
* Description of the Mark-and-Recapture: https://en.wikipedia.org/wiki/Mark_and_recapture
  (Feel free to google more math behind it, I'm sure there's more out there)

# Appendix 2. In-class notes and activities

Week 1. Intro

* Technical concepts
  * Jupyter, how to work with cells.
  * Elementary python. Variables, lists. Loops. Conditions. Simple output. 
  * Markdown
  * Github and Gitkraken.
  * Numpy. Vectorized operations. Differences between numpy objects and lists.
  * Copying by reference and deep copying.
  * Functions.
  * Matplotlib.

* Possible simple assignments:
  * Birthday paradox
    * First numerically
    * Then test by sampling, and plot on the same plot
  * Collatz conjecture: first build some plots, then find longest path under 100 and visualize it
  * Random walk: betting 1 at a time, starting at 10, probability of outcomes after N bets (build a histogram)
  * The one with a triangle and moving to corners?

Week 2. Logistic growth. Numerical integration. Model parameters, qualitative answers. Chaos. Sensitivity to starting conditions.

* Idea of numerical integration. Movement of objects: cannonball, visualize, add friction
* Logistic growth. Try different growth rates. Note changes.
* Formulate a prediction. 
* Systematic exploration of parameter space.
* Bifurcation diagram.
* Explore sensitivity to starting conditions, for 2-3 different values of alpha.

Week 3. Predator-prey ODEs (Lotka–Volterra).

* Recreate equations from basic principles?
* Parameterize, visually explore
* How to quantify behaviors?
* Explore the parameter landscape
* Make meaningful predictions

Week 4. Agents. Objects. Catch-release model. Effects of geometry.

* Make the model. Start with a square torus geometry. Plot data over time. Compare final state with the theoretic prediction.
* Replace square torus with bouncy walls. Can we notice a difference?
* Change the shape from a square to increasingly elongated. Can we notice a difference? Can we infer something about the shape from the data?
* ??? Any next steps?

