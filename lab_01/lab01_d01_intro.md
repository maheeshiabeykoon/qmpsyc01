# Lab 1: Introduction to R & RStudio

## What is R?

R is a programming language and software environment built for statistical computing, data analysis, and visualization. It was originally developed by statisticians, it's now used by researchers across many fields including psychology as a primary tool for analyzing data.

```{image} ../images/R_logo.png
:alt: R logo
:class: bg-primary
:width: 150px
:align: center
```

A few reasons R is popular with researchers:

- Free and open-source. Unlike SPSS or SAS, R costs nothing and can be installed on any computer, with no license restrictions.
- A huge library of packages. User-contributed packages extend R to cover almost any statistical method, from t-tests to structural equation modeling.
- A manageable learning curve. Even students with no programming background can learn enough R in the first few weeks of a course to run and interpret common analyses.
- Well suited to psychology. R makes it easy to go from raw data to a finished analysis and figure in one reproducible script, and that make life easier for psychological research.

### Two Components of the R Language
 
When people talk about "using R," they are usually referring to two related pieces:
 
1. **Base R** — This is the core language and set of built-in functions that you get when you download R itself. Base R already includes tools for basic data manipulation, descriptive statistics, and many standard statistical tests.
2. **R Packages** — These are add-on libraries, written by members of the R community, that extend base R's capabilities. Most packages are hosted on the **Comprehensive R Archive Network (CRAN)**, a centralized repository that maintains vetted, quality-checked packages. Throughout this course, you will install and use several packages (e.g., for data wrangling, visualization, and specific statistical models).

### Installing R

You can download R itself along with instructions for Windows, macOS, and Linux from the official R Project website: 🔗 **[https://www.r-project.org/](https://www.r-project.org/)** 

**Steps**:
"Download R" → choose a CRAN mirror → select your operating system

---

## What is RStudio?
 
R on its own runs through a fairly bare-bones console, which can feel unfriendly to new users. **RStudio** is a free, open-source **Integrated Development Environment (IDE)** that provides a graphical interface for working with R. It does not replace R, still you need R installed on your computer  but it sits "on top" of R and makes everyday work much easier by combining several things you need into one window: a script editor, a console, a viewer for plots and tables, and a file/package manager.
 
For this course, you will do virtually all of your work inside RStudio, since it makes writing, running, and organizing R code (other types of R code files: R Markdown,Jupyter documents) far more manageable than using R alone.
 
### Installing RStudio

RStudio (now developed by Posit) can be downloaded here:<br>
🔗 **[https://posit.co/download/rstudio-desktop/](https://posit.co/download/rstudio-desktop/)**
> **Note:** Install R *first*, and then install RStudio. RStudio will automatically detect the R installation on your computer.
 
---

## Learning Resources for R
 
Because R is free, open-source, and enormously popular, there is a wealth of high-quality, freely available material for learning it well beyond what we can cover in lab sessions. You are strongly encouraged to explore these resources throughout the semester, especially when you want a different explanation of a concept or a deeper dive into a topic.
 
### Free online books

- *Learning Statistics with R* by Danielle Navarro -  written specifically for psychology students: [https://learningstatisticswithr.com/](https://learningstatisticswithr.com/)
- *Hands-On Programming with R* by Garrett Grolemund - [https://rstudio-education.github.io/hopr/](https://rstudio-education.github.io/hopr/)
- *R for Data Science* (2nd ed.) by Hadley Wickham, Mine Çetinkaya-Rundel, and Garrett Grolemund - [https://r4ds.hadley.nz/](https://r4ds.hadley.nz/)
- *An Introduction to R* (the official CRAN manual) - [https://cran.r-project.org/doc/manuals/r-release/R-intro.html](https://cran.r-project.org/doc/manuals/r-release/R-intro.html)

### Interactive and video resources

- YouTube hosts many free tutorial series and full courses on R, covering everything from basic syntax to advanced statistical modeling.
- Platforms such as Coursera, DataCamp, and edX also offer structured R courses, some of which are free to audit

