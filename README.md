## Homework

*Don't make copies of files. These are yours. Edit them and save. For homework,*
*edit `hwXX.Rmd` and knit. Then commit both `hwXX.Rmd` and `hwXX.pdf`.*

This repository contains (or will contain) all of the possible homework
assignments you can complete.



__Remember__


## Due dates

* HW1 28 September 
* HW2 17 October
* HW3 2 November
* HW4 21 November
* HW5 7 December


## Process

* First, you must `clone` this repo to your machine. You only need to do this 
once. The easiest way is with an RStudio Project. 
File > New Project > Version Control > Git. 
Then copy the url into the first field. 
You can save anywhere you like on your machine. 

* Now you're ready to go. So you want to start working...

* The below is the same as at [Stat-406/FAQ](https://ubc-stat.github.io/stat-406/faq/)

**If you are confused or concerned SAVE YOUR WORK and then post to Slack for help**


### Workflow in an RStudio Project

1. Make sure you are on `main` (Check the dropdown on the git tab.) 
Pull with the Blue Arrow ⬇️.
1. Create a new branch (name it anything you like).
1. Work on your documents and save frequently.
1. Stage your changes by clicking the check boxes.
1. Commit your changes by clicking **Commit**. 
1. Repeat 3-5 as necessary.
1. Push to GitHub with the Green Arrow ⬆️.
1. When done, go to GitHub and open a PR.
1. Use the dropdown menu to go back to `main` and avoid future headaches.

### Workflow from the command line

1. Make sure you are on `main`: `git branch -v`. If not on `main`: 
`git checkout main`.
1. Pull in any remote changes: `git pull`
1. Create a new branch `git branch -b <name-of-branch>`
1. Work on your documents and save frequently.
1. Stage your changes `git add <name-of-document1>` repeat for each changed 
document. `git add .` stages all changed documents. `git status` lists changed
documents.
1. Commit your changes `git commit -m "some message that is meaningful"` 
1. Repeat 3-5 as necessary.
1. Push to GitHub `git push`. It may suggest a longer form of this command, 
obey. 
1. When done, go to GitHub and open a PR.
1. Switch back to `main` to avoid future headaches. `git checkout main`.

