# 31.10.2017

## What is our progress on the project?
See [progress document](https://docs.google.com/document/d/1Q_i7b16EZrtadMW4Cx1csgCxGNm24Putf_u-kMu6aQc/edit?usp=sharing).


## Writing sprint / hackathon
- Heidi will redo the doodle: only weekends ([link](https://doodle.com/poll/7dc4cecct83e3ei5))
- OpenPizza?
- Let's try to figure out how to pay people
- Heidi sends out an email with the doodle

## Organisation of the project next year
- Heidi will start a postdoc and cannot do organisation + helping
- Does anyone want to lead the project starting 2018?
- Peter would be interested after solving his primary employment problem.
- If we don't find anyone Cedric and David would also take over (this is not our preferred solution)

# 17.10.2017

## Reorganisation of the project

### [Communication in gitter](https://gitter.im/mozilla/open-leadership-training)

### [Organisation Document](https://docs.google.com/document/d/1Q_i7b16EZrtadMW4Cx1csgCxGNm24Putf_u-kMu6aQc/edit?usp=sharing)

### [GitHub issues](https://github.com/school-of-data/r-consortium-proposal/issues)


## Moving foward

1. Where are we on the data recipes?
2. Where are we on the skills lessons?


# 03.10.2017

## Report from summer camp (Peter)
Very educational, 30 people from 20 countries

Camila, a R expert from Turkey and Peter met

- Keep in mind that data journalists are not very computer literate
- Not advanced excel users
- Need to explain each step in depth; much more than now (maybe not all of the material)
- Peter got the names of some people who would be interested to test the material


## Discussion based on Peter's report

- Recipes should be self consistent and not refer to other recipes.
- Refering to the very short skills lessons should be o.k., but it should mostly be self consistent.
- Idea: use RStudio cheatsheets in skills lessons


## Progress

### Making it easy for people to navigate the project (Heidi)
#### README and CONTRIBUTING
Heidi created a [README.md](https://github.com/school-of-data/r-consortium-proposal/blob/master/README.md) and a [CONTRIBUTING.md](https://github.com/school-of-data/r-consortium-proposal/blob/master/CONTRIBUTING.md) to help interested people figure out how to help.

#### Templates
The templates should make it easy to contribute:
```
devtools::install_github("school-of-data/r-consortium-proposal", 
                         subdir = "r-package")
learnr::run_tutorial("en-recipe-template", package = "ddj")
learnr::run_tutorial("en-skills-template", package = "ddj")
```

### General intro lesson (Camila)
- Intro lesson on data analysis (es)
- Intro lesson on data viz (es)


## TODOs until next tuesday

- Samuel: works on his recipe, asks Joel if he still wants to do a recipe on data from his article, put RStartHere in "further reading", set up a call for next week
- Heidi: create some issues for hacktoberfest https://hacktoberfest.digitalocean.com/
- Peter: contact data journalist from Turkey, asking for data and/or code


# 05.09.2017

## Contract
The contract with the R consortium asks in exhibit A to define deliverables/milestones and their due date to get payments. As it's a legally binding document that I will sign on behalf of OK France, I just want to make sure we agree on it. 
We agreed that, as the project is moving on slowly (but still moving on), we should not have deadlines that are not reachable. We need to take time to do it properly so here is the proposed schedule : 
Writing of the materials: end-2017
Translation of the materials: March 2018
Design, developpement and launch of the website: June 2018
If it's ok with you guys by the end of the week, I will send it to the R consortium. 

## Guidelines
Peter suggested that we have guidelines for harmonising the materials and setting the expectations of what would be a good recipe on terms of intended audience, expectations, structure, presentation… 
We also mentioned that recipes should have a further reading section (instead of learning tracks in the initial proposal) 
Heidi will start drafting the guidelines with my help. 

## Basic skills 
Peter suggested that we should start with a basic skills lesson, something very basic to bring people on board of R. 
To be explored further

## Call for proposals
After the guidelines are agreed, we might send a call for proposals out there to have maybe 2 additionnal recipes. 
To be explored further


