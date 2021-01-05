# Tech Radar

This repository contains all past and upcoming tech radars for the department. Tech Radars are useful for discussing our current tech ecosystem, what we find useful in our teams, what we want to decommission and what we want to try.

## Contents

- [Tech Radar](#tech-radar)
  - [Contents](#contents)
  - [Current Tech](#current-tech)
    - [Current State of Tech Radars](#current-state-of-tech-radars)
  - [## Tech Radars](#-tech-radars)
    - [Past Radars](#past-radars)
  - [## Structure](#-structure)
  - [## Terminology](#-terminology)
    - [Blips](#blips)
    - [Quadrants:](#quadrants)
    - [Rings:](#rings)
      - [For Current State Of Tech:](#for-current-state-of-tech)
      - [For Tech Radar:](#for-tech-radar)
  - [## Contribution](#-contribution)
    - [Adding to the radar](#adding-to-the-radar)
    - [Testing Your Changes](#testing-your-changes)

## Current Tech

These radars show what platforms, languages and frameworks, tools and techniques the teams recommend, which are in limited use currently, which are in active trial and which shouldn't be used with explanation.

* *Recommended* - Is in frequent use, is well known and battle hardened by the team.
* *Limited Use* - Is used in some places and there is some knowledge around it.
* *In Trial* - Has been discussed as an option and is being trialed in a PoC or project.
* *Do Not Use* - Has been tried and is not recommended for our use case unless something has dramatically changed.

### Current State of Tech Radars

- [2020](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fraw.githubusercontent.com%2Fwordshaker%2Ftechradar%2Fwordshaker%2Fseperate-current-tech%2FCurrentStateOfTech%2F2020.csv)

## Tech Radars
---

These radars are for tech currently in discussion and trial. What we want to trial, adopt, assess or hold research on.

* *Adopt* - Mature and ready for use. You should be using these technologies if they are appropriate for your problem.
* *Trial* - Proven to be ready for use but not yet widely used. Should be carefully monitored when used in production.
* *Assess* - Something new that we are excited about but not yet sure it is production ready. Evidence why it solves a particular problem should be collected through some kind of POC.
* *Hold* - We know these are not ready for use or we are actively avoiding going forward.

### Past Radars

- [Q1](https://radar.thoughtworks.com/?sheetId=https%3A%2F%2Fraw.githubusercontent.com%2Fwordshaker%2Ftechradar%2Fmain%2F2020%2FLAA%25202020%2520-%2520Q1.csv)

## Structure
---

All the technical opinions are captured as individual rows in a table kept in a CSV file. See a template [here](template.csv)

The opinions are categorised into quadrants and rings on the radar as per the ThoughtWorks tech radar format.  


## Terminology
---

### Blips
These are the points on the radar which can be opened for more information.

### Quadrants:
* Languages & Frameworks - What we write our software in (Development)
* Platforms - What we run our software systems on and where we persist our data (Operations)
* Tools - What we use on the side to improve the way we develop and operate our systems (Dev & Ops)
* Techniques - What methods & practices we follow

### Rings:

#### For Current State Of Tech:

* Recommended - Is in frequent use, is well known and battle hardened by the team.
* Limited Use - Is used in some places and there is some knowledge around it.
* In Trial - Has been discussed as an option and is being trialed in a PoC or project.
* Do Not Use - Has been tried and is not recommended for our use case unless something has dramatically changed.
  
#### For Tech Radar:

* Adopt - Mature and ready for use. You should be using these technologies if they are appropriate for your problem.
* Trial - Proven to be ready for use but not yet widely used. Should be carefully monitored when used in production.
* Assess - Something new that we are excited about but not yet sure it is production ready. Evidence why it solves a particular problem should be collected through some kind of POC.
* Hold - We know these are not ready for use or we are actively avoiding going forward.

For more information please see the [ThoughtWorks Tech Radar FAQ](https://www.thoughtworks.com/radar/faq).


## Contribution
---
There will be meetings set to discuss what should be in each quarters radar. These meetings will be open to all who wish to contribute suggestions for additions, removals and re-categorisations.

Please follow the contributing guidelines [here](CONTRIBUTING.md)

### Adding to the radar

For making changes to the upcoming radar for discussion, please open a new branch, and make your changes on that branch and raise it for PR. 

In the meeting, all PR's will be gone through and discussed. If agreed upon, the changes will be merged.

### Testing Your Changes

It's best to test any changes you want to the radar CSV file by pushing them to github in a new branch (as per the contributing guidelines above). Navigating to the radar CSV file on github for your new branch (not on main!) and select the "Raw" view of the file. You can then copy the link to this file and enter it into the [ThoughtWorks radar tool](https://radar.thoughtworks.com) to render it with your changes.