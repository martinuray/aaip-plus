---
layout: page
title: Project Description
nav_exclude: true
description: >-
    Description, Instruction, Scope, and Grading for the course project 
---

# Course Project: The history of the modern Olympic Games
{:.no_toc}

{: .note }
> Unlike other pages of this webpages, this project description applies to both
> courses at PLUS and at SUAS.

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---
## The Project
In this project, you will explore a dataset containing detailed information 
about the modern Olympic Games, spanning from Athens 1896 to Rio 2016. 
The dataset, which is available on Moodle or Kaggle, includes data on athletes, 
events, countries, and medal counts over this time period.

Your task is to select a specific aspect of this dataset to visualize, such as:

- The evolution of participating nations and athletes over time
- Medal distributions by country, gender, or sport
- Trends in the performance of specific countries or regions
- The impact of political events (e.g., boycotts) on participation or results
- Any other topic of your interest related to the Olympic Games

The goal is to present your findings and insights in a visual format using 
charts, graphs, or infographics. 
Your final deliverable will be an A3 poster (or larger, depending on your 
preference) that clearly communicates your chosen aspect of the Olympic Games.   


## The Dataset
The dataset can be found [here on Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
and consists of two csv files.
Here, a brief description is given:

- The file `athlete_events.csv` contains individual athletes competing in an 
individual Olympic event.

| **Feature** |        **Description**         |
|:-----------:|:------------------------------:|
|    _ID_     |   Unique ID for each athlete   |
|   _Name_    |         Athlete's name         |
|    _Sex_    |              F/M               |
|    _Age_    |         Athlete's Age          |
|  _Height_   |     Athlete's body-height      |
|  _Weight_   |     Athlete's body-weight      |
|   _Team_    |           Team name            |
|    _NOC_    |   3-letter code for the NOC    |
|   _Games_   |        Year and season         |
|   _Year_    |   Year of the Olympic Games    |
|  _Season_   |     Summer or Winter Games     |
|   _City_    | Host City of the Olympic Games |
|   _Sport_   |         Type of Sport          |
|   _Event_   |   Event of the participation   |
|   _Medal_   |  Gold, Silver, Bronze, or NaN  |

- The file `noc_regions.csv` contains the country names corresponding to the
National Olympic Committee (NOC) codes.

| **Feature** |       **Description**       |
|:-----------:|:---------------------------:|
| _NOC_       | 3-letter code for the NOC   |
| _Region_    | Country Name                |
| _Notes_     | Additional Notes to the NOC |

## The Task

After exploring the dataset, formulate a key question/topic for your final project. 
This topic should focus on a specific aspect of the  dataset, e.g.

- Alpine Skiing Men's Giant Slalom Medalists over the years
- Athletes with the most participation in the Olympic Summer Games (Overall/Per Sport etc.)
- Medalists from your home country
- All-time medal table for your favorite sport
- Niche Sports with the least number of participants
- One-Hit-Wonders (Sports that were only part of few Olympic Games)
- ...

Use different visualization options to show in-depth analyses of your topic.
Besides "basic" plots, think of including maps for geographic distributions, 
show time series, and be sensitive about choices of colors, marker styles, 
legend, and labeling (see Data Visualization 101).
The more interesting, the better!

{: .note } 
> Your poster needs to include at least __three__ different kind of plots.
> A simple bar- or line-plot is not sufficient. 


## Getting to know the Dataset and the EDA
So to get started, you should first get to know the dataset.
To give you a head start, there are some predefined questions you can 
answer, to get an initial understanding of the dataset.

To start off, use
[**this Jupyter Notebook**{: .label .label-green }](../assets/course_material/notebooks/FinalProject_EDA.ipynb).
The notebook contains some initial questions and code snippets to get you
started with the dataset.

{: .tip}
> GeoPandas: For Windows users, with pip the installation does not work 
> out-of-the-box. 
> See [this link](https://towardsdatascience.com/geopandas-installation-the-easy-way-for-windows-31a666b3610f)
> for a guide on how to install GeoPandas on Windows accordingly.

**Done with those questions?** 
Start working on your own questions!
What is of interest to you? 
Try to find a question that you can answer with the dataset and that is
interesting to you.


## The Final Presentation
The final presentation will take place as a poster session on the very last 
day of the course, as communicated via schedule.

Be prepared to  present your **printed** poster in a 5-minute  pitch.

### Poster Requirements
- choose a suitable topic and title and include it in your poster
- add an abstract to motivate your project (between 800-1000 character)
- add a paragraph with your key findings (between 1000-1500 character)
- include at least 3 different kinds of plots (created using Python) in  
  your poster. Each plot should have a title, legend, labels, and should be 
  self-explanatory
- include your name and the course title on the poster
- make sure the poster is visually appealing
- Optional: link or QR code to further information

{: .tip }
> **What does a poster need and how to design one?**
> - [this](https://guides.nyu.edu/posters/poster-basics) is a cool, but short, guideline on how to make a good scientific poster
> - [this short video](https://www.youtube.com/watch?v=AwMFhyH7_5g) explains how a _good_ research poster is structured 

{: .tip }
> **What to use to design your poster?**
> - [Powerpoint](https://www.makesigns.com/SciPosters_Templates.aspx) 
> - [LaTeX](https://de.overleaf.com/gallery/tagged/poster)
> - see the links on the previous tip

### Poster Submission
Before the presentation, the poster has to be submitted as a PDF via
- **ITS Students:** upload the poster to the submission in the e-Learning course;
  Deadline as communicated via the submission form.
- **PLUS Students:** drop your poster into [this OneDrive Folder](#); **Deadline:** 
  2025-01-27, 6.00 pm.

{: .important }
> The submission links will close at the communicated time and students will 
> not be able to submit anything beyond this date.
> This implies that a presentation during the poster session is not graded.

### Poster Session
The presentation during the poster session is not fully mandatory for the 
course completion (however, [Syllabus, Attendance](../about/#attendance) still 
applies), however, the presentation has substantial account to the overall 
grade (see [AAIP Syllabus](../about/) or [DAPIL Syllabus](https://elearn.fh-salzburg.ac.at/pluginfile.php/68377/mod_resource/content/4/syllabus.pdf)).

**How will this poster session work?**
The poster session will be on site in the last class (date, time and place 
communicated via the class schedule).
The group of students submitted the poster on time are eligible to present 
their poster.
These students will be grouped into two or more sessions.
The grouping is announced at the beginning of the poster session.

Every student will put up his/her poster (printed) on a pin-board. 
Students not in the current session and the instructor have the chance to go 
around and check the others posters.
In total, the 5-min presentation will be given several times.
This format also fosters discussions about all the topics and to give 
students a chance to see the other student's results.

{: .caution }
> The poster needs to be printed at a minimal size of A3. 

{: .tip }
> For SUAS Students:
> The printing can be done on site, at SUAS. 
> Find information on the location of  printers and their capabilities at 
> [myfhs](https://myfhs.fh-salzburg.ac.at).

## Grading
The grading of the project will be based on several components and a
combination of the following factors:

- visual presentation using the poster
- design and usage (variety) of plots, formal requirements of plots
- the topic of the project and the story told
- the short verbal presentation of the poster

{: .note }
> For SUAS Students:
> The grading will be done by two of the course instructors. 

The grades of the project (and the overall grade of the course) will be 
communicated in a timely manner.
