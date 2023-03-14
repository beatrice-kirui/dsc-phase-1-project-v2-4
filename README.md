# Phase 1 Project Description

![awesome](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v2-4/master/awesome.gif)

In this project description, we will cover:
Overview
This repository helps to explore relationships between runtime, gross, num_votes and genre. Runtime: The best selling and low_budget movies are neither short nor long rather around 90 minutes long.Documentaries are the most watched and profitable movies.Num_votes was high for long movies.
## Project Overview

##For this project, you will use exploratory data analysis to generate insights for a business stakeholder.
This are my visulizations for the data i analysed.

![image](https://user-images.githubusercontent.com/124546863/225161234-d7d7188f-9d3a-4e66-a73c-2e1d7e7218fb.png)
![image](https://user-images.githubusercontent.com/124546863/225161266-3af89b51-13d4-48d7-ace2-06ceac4945a3.png)
![image](https://user-images.githubusercontent.com/124546863/225161326-a2c4f013-ba40-48ff-8946-dd98a4598063.png)


### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### The Data

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

I used :
* [IMDB](https://www.imdb.com/)
* [Box Office Mojo](https://www.boxofficemojo.com/) for my analysis.

Because it was collected from various locations, the different files have different formats. Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software or `pd.read_csv`, while the data from IMDB is located in a SQLite database.

![movie data erd](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v2-4/master/movie_data_erd.jpeg)

Note that the above diagram shows ONLY the IMDB data. 

### Questions To consider
Is the movie profitable? Most movies are profitable and shown by the GDP graph.
What type movie making more money? Documentaries are making more money as they are most wathed as opposed to 'Comedy,Drama,Romance'.
Total profit is important in understanding the total amount of money that can be made making movie.
The mean votes will determine how the movie studio relates with the parent company which is Microsft.


## Deliverables

There are three deliverables for this project:

* A **non-technical presentation**
* A **Jupyter Notebook**
* A **GitHub repository**

#Methods
Libraries used were pandas, sqlite3, numpy ,seaborn, matplotlib.pyplot, scipy and %matplotlib inline.


### Non-Technical Presentation

For further reading on creating professional presentations, check out:

* [Presentation Content](https://github.com/learn-co-curriculum/dsc-project-presentation-content)
* [Slide Style](https://github.com/learn-co-curriculum/dsc-project-slide-design)

### Jupyter Notebook

The Jupyter Notebook is a notebook that uses Python and Markdown to present your analysis to a data science audience.

* ***Python and Markdown*** 
  * Markdown should be used to frame the project with a clear introduction and conclusion, as well as introducing each of the required elements.
* ***Data science audience*** 
Along with the presentation, the notebook also describes the project ***goals, data, methods, and results***. It must include at least ***three visualizations*** which correspond to ***three business recommendations***.

The graded elements for the Jupyter Notebook are:

* Business Understanding
* Data Understanding
* Data Preparation
* Data Analysis
* Visualization
* Code Quality

See the [Grading](#grading) section for further explanation of these elements.

### GitHub Repository

The GitHub repository is the cloud-hosted directory containing all of your project files as well as their version history.

A professional GitHub repository has:

1. `README.md`
    * A file called `README.md` at the root of the repository directory, written in Markdown; this is what is rendered when someone visits the link to your repository in the browser
    * This file contains these sections:
       * Overview
       * Business Understanding
          * Include stakeholder and key business questions
       * Data Understanding and Analysis
          * Source of data
          * Description of data
          * Three visualizations (the same visualizations presented in the slides and notebook)
       * Conclusion
          * Summary of conclusions including three relevant findings
2. Commit history
   * Progression of updates throughout the project time period, not just immediately before the deadline
   * Clear commit messages
   * Commits from all team members (if a group project)
3. Organization
   * Clear folder structure
   * Clear names of files and folders
   * Easily-located notebook and presentation linked in the README
4. Notebook(s)
   * Clearly-indicated final notebook that runs without errors
   * Exploratory/working notebooks (can contain errors, redundant code, etc.) from all team members (if a group project)
5. `.gitignore`
   * A file called `.gitignore` at the root of the repository directory instructs Git to ignore large, unnecessary, or private files
     * Because it starts with a `.`, you will need to type `ls -a` in the terminal in order to see that it is there
   * GitHub maintains a [Python .gitignore](https://github.com/github/gitignore/blob/master/Python.gitignore) that may be a useful starting point for your version of this file
   * To tell Git to ignore more files, just add a new line to `.gitignore` for each new file name
     * Consider adding `.DS_Store` if you are using a Mac computer, as well as project-specific file names
     * If you are running into an error message because you forgot to add something to `.gitignore` and it is too large to be pushed to GitHub [this blog post](https://medium.com/analytics-vidhya/tutorial-removing-large-files-from-git-78dbf4cf83a?sk=c3763d466c7f2528008c3777192dfb95)(friend link) should help you address this

### Attention to Detail

If you have searched for a job, you have probably seen "attention to detail" appear on a job description. In a [survey of hiring managers](https://www.payscale.com/data-packages/job-skills), fully 56% of them said they felt that recent college grads lacked this skill. So, what does "attention to detail" mean, and how will you be graded on it at Flatiron School?

Attention to detail means that you accomplish tasks thoroughly and accurately. You need to understand what is being asked of you, and double-check that your work fulfills all of the requirements. This will help make you a "no-brainer hire" because it helps employers feel confident that they will not have to double-check your work. For further reading, check out [this article](https://www.indeed.com/career-advice/career-development/attention-to-detail) from Indeed.

***Attention to detail will be graded based on the project checklist. In Phase 1, you need to complete 60% (6 out of 10) or more of the checklist elements in order to pass the Attention to Detail objective.*** The standard for passing the Attention to Detail objective will increase with each Phase, until you are required to complete all elements to pass Phase 5 (Capstone).

