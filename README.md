# EDA_The_Github_History_of_the_Scala_Language
Exploring the Scala developing history on GitHub since 2011 to 2018.
This project is part of [Data Scientist with Python](https://app.datacamp.com/learn/career-tracks/data-scientist-with-python?version=5) Career path on [Datacamp](https://app.datacamp.com/learn)

## Files:
* The Githib History of the Scala Language.ipynb: EDA File of the [Scala History on GitHub](https://www.kaggle.com/datasets/utshabkumarghosh/the-github-history-of-the-scala-language).
* pulls_2011-2013.csv contains the basic information about the pull requests, and spans from the end of 2011 up to (but not including) 2014.
* pulls_2014-2018.csv contains identical information, and spans from 2014 up to 2018.
* pull_files.csv contains the files that were modified by each pull request.
* pulls.csv: contains the ids and names of the individuals who made the pull requests.

## EDA Steps:
1. Starting with appending data from pulls_2011_2013.csv as pulls_one and pulls_2014_2018 as pulls_two into pulls.
2. Then, Merging pulls from step1 and pull_files.csv as pull_files into data.
3. Figuring out whether the development of Scala is still active on GitHub.

![BarChart01](https://github.com/Nour-Ibrahim-1290/EDA_The_Github_History_of_the_Scala_Language/blob/main/Scala-History-GitHub-BarChart.PNG?raw=true)

4. Tracking what files has been changed recently.
5. Who contributed the most on the development process (most pull requests).
6. Who made the last 10 pull requests on a specific file.
7. The pull requests History of 2 Special Developers.
8. Visualing the contribution of both ['xeno-by', 'soc'].

![BarChart01](https://github.com/Nour-Ibrahim-1290/EDA_The_Github_History_of_the_Scala_Language/blob/main/Scala-History-GitHub-BarChart02.PNG?raw=true)

## Using these Python Libraries:
* [Pandas](https://pandas.pydata.org/docs/)
* [Matplotlib.pyplot](https://matplotlib.org/stable/users/index.html)
* [seaborn](https://seaborn.pydata.org/)
