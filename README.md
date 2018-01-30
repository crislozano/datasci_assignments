datasci\_assignments
====================

Programming assignments for Data Science for Linguistics.

-   [pa1](#assignment-1)
-   [pa2](#assignment-2)

------------------------------------------------------------------------

Assignment 1
------------

**Topic**: GitHub

### Overview

In this assignment you will practice the basics of working with project
repos using GitHub and the GitHub desktop app. Specifically, you will
fork this repo, clone it to your computer, contribute to it, push
changes from your local repo (your computer) to your upstream branch
(your forked copy on GitHub), and, finally, submit a pull request to
merge your contribution with the master repo (the professor's copy).

**Assigned**: Week 1  
**Due**: Monday, 1/22 before 10pm

### Instructions

1.  If you have not already done so, fork this repo and clone it to your
    computer.
2.  In your local copy create a personal 'dropbox'
    1.  create an empty folder named "lastname\_firstname" (ex.
        casillas\_joseph). Put it inside `misc > students`.
    2.  create another **README.md** file and place it inside your
        personal folder. Include the following info:
        -   Your name
        -   Your email
        -   Your personal website if you have one
        -   A goal you have for this class

3.  Create another folder. Name it `summaries` and place it inside your
    personal dropbox folder. Next, read [Wickham,
    2015](https://nhorton.people.amherst.edu/mererenovation/17_Wickham.PDF).
    Create a file called **wickham\_2015\_summary.md** and write a 4
    sentence summary about the article. Save this file in `summaries`
    inside your personal dropbox (the lastname\_firstname folder you
    just made).
4.  Read [R4DS](http://r4ds.had.co.nz/index.html) Preface - Ch. 2 (p.
    ix-41). Do all examples included in the text as you read (nothing to
    turn in).
5.  Read QML Ch. 1 (pp. 1-33). Do the R examples included in the text as
    you read (nothing to turn in).
6.  Commit the changes to your upstream branch. Check your repo on
    GitHub to make sure it worked, and then submit a pull-request. It
    should include the following...
    1.  your dropbox folder (lastname\_firstname)
    2.  a README.md file
    3.  a summaries folder (inside your dropbox)
    4.  your Wickham (2015) summary (wickham\_2015\_summary.md)

### Evaluation

This is programming assignment 1 of 4. It is worth 10 of the 40 possible
points. In order to receive full credit you must complete steps 1-6
above and follow all the instructions.

<table>
<thead>
<tr class="header">
<th align="left">Task</th>
<th align="right">Points</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Create a dropbox folder</td>
<td align="right">1</td>
</tr>
<tr class="even">
<td align="left">Include a README.md</td>
<td align="right">1</td>
</tr>
<tr class="odd">
<td align="left">Create a summaries folder</td>
<td align="right">1</td>
</tr>
<tr class="even">
<td align="left">Include a summary of Wickham (2015)</td>
<td align="right">2</td>
</tr>
<tr class="odd">
<td align="left">Successfully submit a pull request</td>
<td align="right">5</td>
</tr>
<tr class="even">
<td align="left"><strong>Total</strong></td>
<td align="right">10</td>
</tr>
</tbody>
</table>

### Tips

This is how the file structure currently looks:

    datasci_assignments
           │
           ├── README.md
           └── misc
               ├── links
               │   └── README.md
               └── students
                   ├── README.md
                   └── firstname_lastname
                       ├── README.md
                       └── summaries
                           └── wickham_2015_summary.md

Take a look inside the `lastname_firstname` folder if you need an
example (this is highly recommended). Your personal dropbox should look
exactly the same, but with your information, summaries, etc. In other
words, you will add a folder inside `students` that looks like this (I
am using my name, you will use your name):

    casillas_joseph
            │
            ├── README.md
            └── summaries
                └── wickham_2015_summary.md

Remember to check the [GitHub setup
tutorial](http://www.jvcasillas.com/ru_teaching/ru_spanish_589/589_01_s2018/sources/tuts/github_setup/index.html)
if you need help pushing your changes and submitting a pull request.

------------------------------------------------------------------------

Assignment 2
------------

**Topics**: RMarkdown, ggplot

In this assignment you will practice the basics of using .Rmd files to
create dynamic, reproducible reports in .docx, .pdf, or .html format.
Moreover, you will show your data visualization skills using `ggplot2`.

### Overview

**Assigned**: Week 3  
**Due**: Tuesday, 2/6 before 10pm

### Instructions

1.  Fetch the latest updates to `datasci_assignments` to your local
    branch. Review the [GitHub setup
    tutorial](http://www.jvcasillas.com/ru_teaching/ru_spanish_589/589_01_s2018/sources/tuts/github_setup/index.html)
    if you need a refresher.
2.  Create a folder, `pa2`, inside your personal
    dropbox.<sup>[1](#myfootnote1)</sup>
3.  Create an RMarkdown file called `pa2.Rmd`.
4.  Use the following information for the **yaml front matter**:

<!-- -->

    ---
    title: "Programming assignment 2"
    author: "Your name"
    date: "Last update: 2018-01-29 18:20:58"
    output: 
      html_document: 
        highlight: kate
        keep_md: yes
        theme: united
    ---

1.  Install and load the `languageR` package.
2.  Familiarize yourself with three of the following five datasets:
    -   **beginningReaders**
    -   **danish**
    -   **dativeSimplified**
    -   **english**
    -   **spanishFunctionWords**

3.  Inside your `pa2.Rmd` file you will generate 3 different plots using
    `ggplot2`. You must use 3 of the aforementioned datasets (a
    different dataset for each plot). All plots must include informative
    x-, y-axis labels and a title. The plots you must create are:
    1.  A bivariate scatterplot
    2.  A boxplot with different fill colors
    3.  A plot of your choice that includes a `stat_summary` and a
        facet.  

4.  Commit the changes in your dropbox to your upstream branch. Check
    your repo on GitHub to make sure it worked (notice anything cool
    when you check the `pa2` folder?), and then submit a pull-request.
    It should include the following...
    1.  your `pa2` folder
    2.  your `pa2.Rmd` RMarkdown file (and probably a few others)
    3.  3 plots created using `ggplot`

### Evaluation

This is programming assignment 2 of 4. It is worth 10 of the 50 possible
points. In order to receive full credit you must complete all the steps
above and follow all the instructions.

<table>
<thead>
<tr class="header">
<th align="left">Task</th>
<th align="right">Points</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left">Create a pa2 folder</td>
<td align="right">0.5</td>
</tr>
<tr class="even">
<td align="left">Create a pa2.Rmd file</td>
<td align="right">0.5</td>
</tr>
<tr class="odd">
<td align="left">Use correct yaml front matter</td>
<td align="right">1</td>
</tr>
<tr class="even">
<td align="left">Generate 3 specified plots</td>
<td align="right">6</td>
</tr>
<tr class="odd">
<td align="left">Successfully submit a pull request</td>
<td align="right">2</td>
</tr>
<tr class="even">
<td align="left"><strong>Total</strong></td>
<td align="right">10</td>
</tr>
</tbody>
</table>

### Tips

Review Ch. 1 of R4DS for help with `ggplot`. **DO NOT** copy the plots
directly from the book or the internet (I'll know).

This is more or less how your dropbox should look (**Note**: your pa2
folder will have a little more detail than what I have described here.
That is fine):

    casillas_joseph
            │
            ├── README.md
            ├── summaries
            │    └── r4ds_ch1_summary.md
            └── pa2
                 └── pa2.Rmd

<a name="myfootnote1">1</a>: Note: you might have noticed that your
current copy of `datasci_assignments` now includes the dropbox folders
of your classmates. This is on purpose. You are encouraged to review
your classmates assignments. You can learn from them and you will notice
that it is possible to solve data science problems using a variety of
different methods. That being said, you should only review the work of
your classmates **after** the assignment has been turned in.

------------------------------------------------------------------------
