![Project Logo][project_logo]

---

<h4 align="center">Analyzing Critic & Audience Ratings of Popular Movies with <a href="https://en.wikipedia.org/wiki/Python_(programming_language)" target="_blank">Python</a> and <a href="https://en.wikipedia.org/wiki/Microsoft_Power_BI" target="_blank">Power BI</a></h4>

<p align='center'>
<img src='04_RESOURCES/built-with-love.svg'>
<img src='04_RESOURCES/powered-by-coffee.svg'>
<img src='04_RESOURCES/cc-nc-sa.svg'>
</p>

<p align="center">
  <a href="#overview">Overview</a> •
  <a href="#prerequisites">Prerequisites</a> •
  <a href="#architecture">Architecture</a> •
  <a href="#demo">Demo</a> •
  <a href="#support">Support</a> •
  <a href="#license">License</a>
</p>

## Overview

This project focuses on analyzing and finding correlations between the audience and critic ratings for some of the popular movies released between 2009-2011.

The deep-dive analysis of ratings also takes the movie genre and movie budget into account.

The repository directory structure is as follows:

Movies-Ratings-Analysis<br>
├─ 01_DATA<br>
├─ 02_ANALYSIS<br>
├─ 03_DASHBOARD<br>
├─ 04_RESOURCES<br>

The type of content present in the directories is as follows:

**01_DATA**

This directory contains the data that can be directly used for exploratory data analysis and data visualization purposes.

**02_ANALYSIS**

This directory contains the python notebooks that analyzes the clean dataset to generate insights

**03_DASHBOARD**

This directory contains the python notebook with an embedded Power BI report that visualizes the data. The Power BI dashboard contains slicers, cross-filtering and other advance capabilities that end user can play with to visualize a specific facet of the data or, to get additional insights.

**04_RESOURCES**

This directory contains images, icons, layouts, etc. that are used in this project

## Prerequisites

The major skills that are required as prerequisite to fully understand this project are as follows:

- Basics of Python
- Python libraries: Numpy, Pandas, Matplotlib, Seaborn
- Basics of Python Notebooks
- Basics of Power BI

In order to complete the project, I've used the following applications and libraries

- Python
- Python libraries mentioned in [requirements.txt][requirements] file
- Jupyter Notebook
- Visual Studio Code
- Microsoft Power BI

> The choice of applications & their installation might vary based on individual preferences & system settings.

## Architecture

The project architecture is quite straight forward and can be explained through the below image:

<img src="04_RESOURCES/process_architecture.png" alt="process_architecture" width="450" height="350"/>

As per the above workflow; we are first importing data present as numpy matrix from the Python file which is then processed and cleaned with another ETL specific Python script.

Finally; we leverage the clean & analysis-ready dataset for some exploratory data analysis (EDA) using Jupyter Notebook and creating an insightful report using Power BI

## Demo

To be updated.

## Support

If you have any doubts, queries or, suggestions then, please connect with me in any of the following platforms:

[![Linkedin Badge][linkedinbadge]][linkedin] [![Twitter Badge][twitterbadge]][twitter]

If you like my work then, you may support me at Patreon:

<a href="https://www.patreon.com/quantumudit" target="_blank">
<img src="04_RESOURCES/become_a_patreon.png" alt="git" width="170" height="50"/>
</a>

## License

<a href = 'https://creativecommons.org/licenses/by-nc-sa/4.0/' target="_blank">
    <img src='04_RESOURCES/by-nc-sa.png' width=88 height=31>
</a>

This license allows reusers to distribute, remix, adapt, and build upon the material in any medium or format for noncommercial purposes only, and only so long as attribution is given to the creator. If you remix, adapt, or build upon the material, you must license the modified material under identical terms.

<!-- Image Links -->

[project_logo]: 04_RESOURCES/project_cover_image.png

<!-- External Links -->

[requirements]: ./requirements.txt

<!-- Profile Links -->

[linkedin]: https://www.linkedin.com/in/uditkumarchatterjee/
[twitter]: https://twitter.com/quantumudit

<!-- Shields Profile Links -->

[linkedinbadge]: https://img.shields.io/badge/-uditkumarchatterjee-0e76a8?style=flat&labelColor=0e76a8&logo=linkedin&logoColor=white
[twitterbadge]: https://img.shields.io/badge/-@quantumudit-1ca0f1?style=flat&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/quantumudit
