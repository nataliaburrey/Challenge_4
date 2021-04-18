[
<img width="1077" alt="Screen Shot 2021-04-18 at 4 12 14 PM" src="https://user-images.githubusercontent.com/80833988/115163947-ee490700-a060-11eb-8858-b1032f8ca143.png">
](url)


# Challenge_4
Risk Return Analysis
# Analyzing Portfolio Risk and Return

* Analytical framework for a FinTech investing platform

> "For this assignment, I will sort through data for 4 whale (called it for its size and influence) hedge funds : TIGER GLOBAL MANAGEMENT LLC , SOROS FUND MANAGEMENT LLC , PAULSON & CO.INC , BERKSHIRE HATHAWAY INC and analize the data for 2015-2020 based on key risk-management metrics. My base-line for market return will be trading data for S&P 500. My task is to apply the three phases of evaluating risk to determine best hedge fund to invest in for my clients.
"

- [Introduction](#Introduction)
- [Why?](#why)
- [How to Install](#how-to-install)
- [How to use](#how-to-use)
- Technologies used
    - [Libraries](#Libraries)
    - [Interfaces](#Interfaces)



## Introduction

In this Challenge I created a Jupyter notebook that contains quantitative analyst for a FinTech investing platform.
Within the same notebook file, you can find comments for the line of code and  my analysis, including the answers to the questions in the Challenge instructions. 
For each line of code there is comments, necessary titles for the plot and lables for the visualizations are included. 


## Why?

 This platform aims to offer clients a one-stop online investment solution for their retirement portfolios that’s both inexpensive and high quality. To keep the costs low, the firm uses algorithms to build each client's portfolio. The algorithms choose from various investment styles and options.

You've been tasked with evaluating four new investment options for inclusion in the client portfolios. After careful data analyses I chose the fund with the most investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas.


## How to install

* Save remote repo from GitHub to your computer (Desktop): in Terninal type:

```
cd desktop

git clone https://github.com/nataliaburrey/Challenge_4.git
```
now you can find repo on your desktop


* Open a Jupyter Lab: In Terminal type command

```
jupyter lab
```

* In Jupyter Lab access saved repo folder 
* Choose [ risk_return_analysis.ipynb ] file to see the analysis report.



## How to use



## Technologies used

### Libraries


We are using Pandas- a software library written for the Python programming language for data manipulation and analysis.
The following libriries has to be imported:

```
import pandas as pd
from pathlib import Path
%matplotlib inline
import numpy as np
```

In particular, Pandas offers data structures and operations for manipulating numerical tables and time series. It is free software released under the three-clause BSD license.

> " Written in: Python, Cython, C .  
Original author(s): Wes McKinney. . 
License: New BSD License
"

" .... matplotlib inline sets the output of plotting commands is displayed inline within frontends like the Jupyter notebook, directly below the code cell that produced it. The resulting plots will then also be stored in the notebook document" (https://stackoverflow.com/questions/43027980/purpose-of-matplotlib-inline)

"NumPy aims to provide an array object that is up to 50x faster than traditional Python lists. The array object in NumPy is called ndarray , it provides a lot of supporting functions that make working with ndarray very easy. Arrays are very frequently used in data science, where speed and resources are very important". 
(https://www.w3schools.com/python/numpy/numpy_intro.asp)


### Interfaces

* Jupyter Lab
* GitHub
* You can download Anaconda packadge on MacOC [HERE](https://www.anaconda.com/products/individual)
Make sure to use following packedge:

[
![anaconda_python37](https://user-images.githubusercontent.com/80833988/113497395-828b6980-94b8-11eb-918c-df4a446f817d.png)
](url)





## Helps recruiters

* The project was created in collaboration with Berkeley Fintech Bootcamp team: Allan Hall, Joel Gonzales, Siege.
* Tutor Lavina Tang helped me to polish my code and tought me how to run separate parts of code to see if it works every step.
* AskBCS Learning Assistant was used to troubleshoot some of the accuring problems outside of the classroom

---

Feel free to contact me via channels

* Email:(nataliaburrey@gmail.com) 
* LinkedIn: (https://www.linkedin.com/in/natalia-burrey-181822175/)



---

* License

MIT
