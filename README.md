# Self paced Python for Data Science

### Synopsis: 
  A collection of  external python curricula for beginner or intermediate statisticians or who want to level up their python /  data science skills. 

## How to Use This Repository:
***This repo consolidates reading, videos, practices, exercises, and challenges from all over the web to present favorite learning material in a cumulative order that will prepare novice programmers or math students for Data Science projects.***  

## Get Started:
**Key**:
 ![skip](/res_bin/media/skip.png) **skip it** - These sections are supplemental; check out the overview and if you're somewhat familiar with all the concepts feel free to skip. if you find yourself struggling later you can always come back!

  ![skim](/res_bin/media/speed_read.png) **skim it**  - give it a once over to make sure you understand everything in the section
  ![study](/res_bin/media/study.png) **study** - Everything in this section is fundamental to understanding content in following sections

1. [Statistics: Introduction](learn_statistics/00%20-%20Probability%20Outline%20&%20Introduction.ipynb)  ![skim](/res_bin/media/speed_read.png)
	 * Impact of correct and incorrect stats
	 * Key concepts
	 * History   

2. [What is Data Science? Brief Overview](data_science/What%20is%20Data%20Science.md) ![skip](/res_bin/media/skip.png)
	* Extract, Transform, Load
	* Scientific method
	* Deliverables
3. [Statistics: Combinations and Permutations](learn_statistics/01-Permutations_&_Combinations.ipynb) ![study](/res_bin/media/study.png) 
	* Calculate the probability of two independent events occurring
	* Understand how order can effect probability 
4. [Python: Basics](learn_python/01_Basics/01_Basics_Lesson.ipynb) ![skim](/res_bin/media/speed_read.png)
	* Installing python locally vs. using an online compiler
	* fundamental syntax for folks who've never programmed before
5. [Python: Iteration](learn_python/02_Iteration/) ![study](/res_bin/media/study.png) 
	* the bread and butter of python and what makes programming powerful
	* spend as much time as you need on this section
6. Statistics: Probability distributions (under construction)
	* Understand how to describe or simulate simple real world events with probability 
7. [Python:  Functions](learn_python/03_Functions/) ![study](/res_bin/media/study.png) 
	*

 ** = coming soon

## Who this Repository is for:
 If you were planning on learning python and data science on your own this repo is for you! It's intended to point you to an ordered, series of progressively more challenging curricula. After you complete a section, you'll see marked improvement and have the skills needed to solve progressively more challenging data and statistics problems.   It's not intended to be your only resource; you will need to supplement  your learning where you feel your skills are under developed.   

  It's not intended to host course material; instead consider this repo like a "news feed" that aggregates learning streams from around the web. That will allow you to start here and branch out. For example, sites like Coursera have great courses on machine learning fundamentals and stats for  psychology and Khan Academy has better courses on basic probability but neither give you great reading material or larger assignments that you can really dig into. You'll find links to all of those sources here peppered with "reach" assignments for added challenge and my own study sheets for interview prep

## How to Contribute to this Repo:
***Use feature-branch workflow***
```mermaid
graph LR
A(Original Master) --> D(New Master)
A -- branch --> C(Feature Branch)

C -- commit  --> E(Feature Branch)
E -- review --> D
``` 

Clone the Repo:
```bash
git clone git@github.com:john-telfeyan/self-paced-python-for-data-science.git
```
Then please use feature-branch workflow like so; First:
```bash
git checkout -b <feature-name>-<your-name>
```

Add only the required files and use a descriptive commit message like...
```bash
git add learn_python/for_loops.ipnb
git add learn_python/media_files/.
git commit -m "Added the 'FizzBuzz' challenge to for_loops.ipnb"
```
 ...then to push the new feature and I'll proof it before merging it:
```bash
git push --set-upstream origin <feature-name>-<your-name>
```

Thanks for reading and contributing!
<!--stackedit_data:
eyJoaXN0b3J5IjpbMTYyMjY3OTcwNywtMTgxMjg3ODI2NiwtMj
AzMTI5Nzk0MCwtMjI5MzQ5MjA4LC0xNzUzMjA5OTQzLDE5NzQ2
OTg3MDcsLTE2OTA3OTg3MTMsLTE4MTczNjIzNjUsLTQwODA0Mj
U1OV19
-->