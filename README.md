# R4DS Engineering Production-Grade Shiny Apps Book Club

Welcome to the R4DS Engineering Production-Grade Shiny Apps Book Club!

We are working together to read [Engineering Production-Grade Shiny Apps](https://engineering-shiny.org/) by Colin Fay, Sébastien Rochette, Vincent Guyader, Cervan Girard.
Join the #book_club-epgs channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.github.io/bookclub-epgs/).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 1: (began 2021-08-25) - FINISHED*

<details>
  <summary> Past Meetings </summary>

### Section I: Building successful apps

- 2021-09-01: Ch1 Intro to shiny, apps, R and golem: Russ Hyde
- 2021-09-08: Ch2 successful projects: Ryan Metcalf
- 2021-09-15: Ch3 Structuring your project: Ryan Metcalf
- 2021-09-22: Ch4+5 Golem Structure & Workflow: Russ Hyde

### Section II:  Design

- 2021-09-29: Ch6+7 User experience and Developer patience: Federica Gazzelloni

### Section III: Prototype

- 2021-10-06: Ch8: Prototyping in {golem}: Ryan Metcalf
- 0201-10-13: Ch9: Building an “ipsum-app”: Russ Hyde

### Section IV: Build

- 2021-10-13: Ch10 Building the app in {golem}: Russ Hyde

### Section V: Strengthen

- 2021-10-27: Ch11 Testing, Environments: Russ Hyde
- 2021-11-10: Ch12 Version Control: Federica Gazzelloni

### Section VI: Deploy

- 2021-11-17: Ch13 + Appendix A Deploying an App, and the whole workflow: Ryan Metcalf

### Section VII: Optimise

- 2021-11-24: Ch14: The need for optimization: Russ Hyde
- 2021-12-01: Ch15: Common Application Caveats: Federica Gazzelloni 
- 2021-12-15: Ch15 (continued):  Common Application Caveats: Federica Gazzelloni
- 2022-01-05: Ch16: Optimizing {shiny}: Russ Hyde
- 2022-01-12: Ch17: Using JavaScript: Ryan Metcalf
- 2022-01-19: Ch17 (continued): Using JavaScript: Ryan Metcalf
- 2022-01-26: Break
- 2022-02-02: Ch18: A Gentle Introduction to CSS and Wrap-Up: Russ Hyde

</details>

## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI)
2. Fork this repository.
3. Create a New Project in RStudio using your fork.
4. Create a New Branch in your fork for your work.
5. Edit the appropriate chapter file. Use `##` to indicate new slides (new sections).
6. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
7. Commit your changes.
8. Push your changes to your branch.
9. Open a Pull Request (PR) to let us know that your slides are ready.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.github.io/bookclub-URL/).
