# MSACL-intermediate-R-course
Course content for MSACL Data Science 201: Going Further with R

This course is intended for laboratory professionals with a basic command of R and is a follow-up course to the introductory R course at MSACL (Data Science 101). The emphasis of this course will be best practices in applying R to solve problems in mass spectrometry and in the clinical laboratory.

- Instructors: Patrick Mathias & Shannon Haymond
- Past instructors and assistants: Randy Julian & Adam Zabell

## Pre-course work/requirements

- A laptop or workstation with access to the internet, and the ability to download files is required
  - Having 2 screens can be helpful for this type of virtual course: a tablet or other computer dedicated to showing the presentation/screen share separately from the space you are working can help
- Complete the following survey so we can better understand your R experience and what you want out of the course: [MSACL Intermediate R Pre-Course Survey](https://forms.gle/wvC8bBB2PsitKBZY9)
- You are welcome to continue using whatever version of R and RStudio you already have on your computer, but you may run into issues running old versions. Our recommendation (if it won't disrupt your working R environment too much):
  - Install the latest version of R by choosing the closest CRAN mirror here at https://cran.r-project.org/mirrors.html and downloading the version for your operating system
  - If you don't already have a recent version, install the latest version of RStudio Desktop at https://www.rstudio.com/products/rstudio/download/#download 
- Open RStudio and confirm you are able to install packages by running `install.packages(c("tidyverse", "tinytex"), dependencies = TRUE)`
  - **If you do not already have LaTeX installed on your computer, run the following from the RStudio console to install TinyTeX: `tinytex::install_tinytex()`.** Note that you will get error messages when installing on Windows that are OK to click through.
  - In addition to the tidyverse set of packages and tinytex, install additional packages with the following command: `install.packages(c("fs", "janitor", "tidylog", "DBI", "RSQLite", "corrplot", "RColorBrewer", "Metrics", "car", "pROC"), dependencies = TRUE)`
- **Download the class data zip files from [link 1](https://drive.google.com/file/d/1kmYTwlQ_JvQF9bR-tvnmvd5dDgRlj3rf/view?usp=sharing) and [link 2](https://drive.google.com/file/d/1nD-5JoqyJv6-6bmnBbmfNgJzoAJFoSGE/view?usp=sharing) (hit the download button), park them someplace you will remember for the course, and uncompress.**
- If not already installed, install Git per instructions at https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
  - **When installing on a Windows machine, select "Use Git from the Windows Command Prompt"**
- Go to Github at https://github.com and sign up for an account (if you don't have one already)

**Optional but strongly encouraged**
- Please make an effort to complete the following Introduction to GitHub: https://services.github.com/on-demand/intro-to-github/

## Accessing/interacting with the course content

There are multiple ways to access and interact with the course content. We want to minimize any headaches with setting up the course and grappling with finicky work computers, but also hope this is a good opportunity to get oriented with version control and git.
1. Use git functionality in RStudio by creating a project from version control that is "cloned" from the class repository. *We will run through how to do this at the beginning of class.* The advantages of this approach: you won't have to retype or copy & paste code and we will make updates to the repository during class so you will be able to easily pull those to your computer without re-downloading.
1. Download this github repository as a zip file and install it on your computer (e.g. C:\Users\jdoe\Desktop\msacl2018).
1. You can refer to this website and copy and paste content as the course goes long.
1. In the event that there are issues with downloading files, we will have a local copy of the course repository that we can share.
1. We have set up a web-based RStudio instance through RStudio Cloud that has the course content pre-loaded. However, we do want attendees to be comfortable with running RStudio locally so will reserve the use of RStudio Cloud for those with installation issues.

<!---
## Course content

- **Entire text**: [Data Science 201 Text in pdf format](coursework/src/course_text.pdf)
- [Accessing the course](accessing_the_course.Rmd)
- **Lesson 1**: [Adopting principles of reproducible research](01 - Principles of Reproducible Research.Rmd)
- **Lesson 2**: [Getting cozy with R Markdown](lesson2/lesson2.Rmd)
- **Lesson 3**: [Reading files - beyond the basics](lesson3/lesson3.Rmd)
- **Lesson 4**: [Data manipulation in the tidyverse](lesson4/lesson4.Rmd)
- **Lesson 5**: [Blending data sets](lesson5/lesson5.Rmd)
- **Lesson 6**: [Taking plotting to the next level](lesson6/lesson6.Rmd)
- **Lesson 7**: [Exploring data](lesson7/lesson7.Rmd)
- **Lesson 8**: [Predictions using linear regression](lesson8/lesson8.Rmd)
- **Lesson 9**: [Classifications using linear regression](lesson9/lesson9.Rmd)
- **Lesson 10**: [End-to-end - from file import to communication](lesson10/lesson10.Rmd)
--->

## Notes/Disclaimers/Acknowledgments

This course is our attempt to integrate a number of already existing outstanding resources for learning R and put a bit of a mass spec spin on them. We have tried to include as many links to relevant resources as we can and hopefully have not missed relevant sources of material and inspiration. We should call out a number of people and resources that directly or indirectly have provided content and inspiration for this course:

- [R for Data Science](http://r4ds.had.co.nz/index.html), the online textbook by Garrett Grolemund and Hadley Wickham, is invaluable in navigating the tidyverse and learning R in general
- Blog posts and documentation by [Jenny Bryan](https://github.com/jennybc) helped steer the project content and as well as some discussion about packages
- [Data Science in the Tidyverse](https://github.com/AmeliaMN/data-science-in-tidyverse), a RStudio course with materials posted online
- Amy Willis' [Advanced R Course repository](https://github.com/adw96/biostat561) as a resource for understanding content in a longer, advanced R course
- Keith Baggerly and Karl Broman's [Reproducible Research](https://github.com/kabagg/sisbid_2018_rr) module at the [Summer Institute in Statistics for Big Data](https://www.biostat.washington.edu/suminst/sisbid) - a big thank you to Keith Baggerly for all of his input and guidance!
- Method validation and some other content has been borrowed from the [basic R course at AACC](https://github.com/pcmathias/AACC-Introduction-to-R)
