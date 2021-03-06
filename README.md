# VJudge-Contests-Rank-List-Parser
Parse & merge the ranklist of the contests from **vjudge.net** and get the final ranklist in a csv file.

It's helpful in managing training contests & evaluating participants performance automatically.

It takes a text file consisting of the ranklist page links & uses **Selenium** & **Requests** libraries to gather all the necessary information & used the **Pandas** dataframe to make the ranklist.

![GIF demo](images/vjudge.gif) 


## Prerequisites
1. Install python 3 ( https://www.python.org/downloads/ )
2. Install Google Chrome ( Update to latest version if already installed)
3. Install the **requirements.txt** e.g pip install -r requirements.txt

## For Windows
1. download chromedriver.exe and copy it to project folder ( https://chromedriver.chromium.org/downloads )
2. Make Sure the chromedriver version support the chrome version you are using

## Note
1. Make sure that the links are entered in correct format. e.g ( https://vjudge.net/contest/380051#rank )
2. Make sure that you have the chromedriver.exe in the same directory of the project
3. If you don't want to count the upsolved problems, pass **False** as the second argument
4. Ranklist is ordered by descending order of total solved problems.

