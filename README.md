[
<img width="990" alt="Screen Shot 2021-05-11 at 8 20 25 PM" src="https://user-images.githubusercontent.com/80833988/117914014-50c7a880-b297-11eb-983b-9e0e8fbc6390.png">
](url)

# CRYPTO analysis
## Using Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF.

> "A Python / Jupyter Lab analysis comparing SnP investment to the new, developing investment cryptocurrency.
This comparison allows for users to make a choise of most 
"


- [Introduction](#Introduction)
- [Why?](#why)
- [How to Install](#how-to-install)
- [How to use](#how-to-use)
- Technologies used
    - [Libraries](#Libraries)
    - [Interfaces](#Interfaces)



## Introduction

In this Challenge I created a Jupyter notebook with analysis of the ETF data that a SQL database stores. Different data manipulations, like SELECTing data into the separate dataframe, JOINing different tables within a database, slicing data with ORDER and LIMIT function for the purpose of financial analyses.

You can find my report, including the answers to the questions from the Challenge instructions in etf_analyzer.ipynb file. For each line of code there is comments.  Necessary titles for professionally styled interactive hvplot visualizations are included. 

Voilà library were used to deploy the visualizations to a web application. 
Here is the video demonstrating deployment of the library via terminal and brief interaction with it on web.


## Why?


[
<img width="792" alt="Screen Shot 2021-05-08 at 10 35 54 AM" src="https://user-images.githubusercontent.com/80833988/117548325-39639380-afe9-11eb-85d4-e48188f03f50.png">
](url)


(https://courses.bootcampspot.com/courses/740/assignments/10690?module_item_id=168908)

## How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/nataliaburrey/SQL_Financial_Application.git
```

now you can find repo on your desktop


* Open a Jupyter Lab: In Terminal type command

```
jupyter lab
```

* In Jupyter Lab access saved repo folder 
* Choose [ etf_analyzer.ipynb ] file to see the analysis report.



## How to use Voila

Following screenshots and videos of the web application, created by deploying your Jupyter notebook via the Voilà library

To deploy Voilà library via terminal type in code:


```
conda activate dev
cd <relative-path-to-notebook>
voila <notebook_name>

```


[
<img width="705" alt="Screen Shot 2021-05-08 at 10 52 32 AM" src="https://user-images.githubusercontent.com/80833988/117548809-d3c4d680-afeb-11eb-9474-352ea917472e.png">
](url)




The file will be opened into default WEB browser




https://user-images.githubusercontent.com/80833988/117549147-8b0e1d00-afed-11eb-8cf9-645af93aa7f9.mov







Following video demonstrates Interactive Visualisations via hvplot 








https://user-images.githubusercontent.com/80833988/117549047-218e0e80-afed-11eb-8801-e31d702cae9b.mov





## Technologies used

### Libraries


We are using Pandas- a software library written for the Python programming language for data manipulation and analysis.
The following libriries has to be imported:

```
import numpy as np
import pandas as pd
import hvplot.pandas
import sqlalchemy

```

In particular, Pandas offers data structures and operations for manipulating numerical tables and time series. It is free software released under the three-clause BSD license.

> " Written in: Python, Cython, C .  
Original author(s): Wes McKinney. . 
License: New BSD License
"


### Languages 

* Python
* SQL


### Interfaces

* Jupyter Lab
* GitHub



## Helps recruiters

* The project was created in collaboration with Berkeley Fintech Bootcamp team: Allan Hall, Joel Gonzales, Siege.
* Tutor Lavina Tang helped me to polish my code and tought me how to run separate parts of code to see if it works every step.
* AskBCS Learning Assistant channel was used to troubleshoot some of the accuring problems outside of the classroom

---

Feel free to contact me via channels

* Email:(nataliaburrey@gmail.com) 
* LinkedIn: (https://www.linkedin.com/in/natalia-burrey-181822175/)



---

* License

MIT
