### Objectives

-   Learn the basics of using RStudio Cloud
-   Create an R Markdown document
-   Bring data into R
-   Perform simple data transformation tasks

### Installation

In the event that we need to work locally this semester, use the
following instructions to install R Studio.

-   Download R using the following link: <https://cran.rstudio.com/>.
-   Double click the installer and follow the instructions.
-   Download R Studio using the following link:
    <https://rstudio.com/products/rstudio/download/#download>.
-   Double click the installer and follow the instructions.
-   Once R Studio has been installed,
    -   Click Project in the top right
    -   Click “New Project”
    -   Click “Version Control”
    -   Click “Git”
    -   Enter the URL
        <a href="https://github.com/is6491/lab_1_intro" class="uri">https://github.com/is6491/lab_1_intro</a>
        -   Make sure the target folders are where you expect them to be
    -   Click “Create”
-   Once the project is open,
    -   Open the “package\_install.R” file by clicking it in the bottom
        right pane
    -   Run the file by clicking “Source” in the top left pane
-   You should now be ready to go.

### Assignment

-   Start the assignment in Rstudio Cloud (this will create a version
    for yourself that I’ll be able to see).
-   Create a new R Markdown document and give it a snappy title.
-   Create a section called “What I want to learn this semester” and
    write a few sentances about what you hope to get out of this class.
-   Create a second section and name it “Working with data”
-   Task 1
    -   Find one of R’s built-in data sets (use the `data()` function
        for a list).
    -   Use one of the simple functions on this data set. Functions
        include the following.
        -   `select`
        -   `filter`
        -   `arrange`
        -   `mutate`
-   Task 2
    -   Find a data set from the internet, or use a data set you already
        have. Some good resources below.
        -   <a href="https://opendata.utah.gov/" class="uri">https://opendata.utah.gov/</a>
        -   <a href="https://sqlbelle.com/2015/01/16/data-sets-for-bianalyticsvisualization-projects/" class="uri">https://sqlbelle.com/2015/01/16/data-sets-for-bianalyticsvisualization-projects/</a>
        -   <a href="https://www.reddit.com/r/datasets/" class="uri">https://www.reddit.com/r/datasets/</a>
    -   Bring that data into R and store it in a variable.
        -   In the file menu in the bottom right pane you’ll find a
            button to upload data from your computer.
        -   Two extra points will be awarded if you figure out how to
            read the data directly from the web.
    -   Use `group_by`, `summarize` and the pipe `%>%` operator to
        perform an aggregation. Note: the aggregation doesn’t have to
        make sense.
-   Knit your R Markdown file and upload the html output into Canvas.

### Work locally

If you would prefer to work locally, you can fork the following
repository from my GitHub account. Note that I will not be able to see
your assignment if you work this way.Go to the following url and fork
the repo if you would like to work locally.

<a href="https://github.com/is6491/lab_1_intro" class="uri">https://github.com/is6491/lab_1_intro</a>
