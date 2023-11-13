# Premier League Data Analysis

### Objective

The purpose of this project is to analyse previous seasons of the Premier League, focusing on the previous two seasons of the league. The project uses web scraping to get data from [fbref](https://fbref.com/en/)

The project aims to address the following questions:

- What is the relationship between shots on target (SoT) and goals scored?
- What team Captain was the most effecitve over the course of the two seasons? (Wins, Goal Contributions)
- Can shooting statistics predict match outcomes?
- What was the most popular formation?
- Which team won the most games?

### Methods Used

- Web Scraping
- Data Integration
- Data Visulization
- Machine Learning

### Setup

```bash
git clone https://github.com/NathanSmallcalder/PremierLeagueData
```

```bash
pip install -r requirements.txt
```

```bash
python premierLeagueData.py
```
### Data Cleaning

Insert a collumn before the "formation" collumn located at R1 with the following formula;

```
=SUBSTITUTE(R1, "â—†", "")
```




### Acknowledgments

The project used a web scraping script created by [oluwatosin17](https://github.com/oluwatosin17), the project can be found [at](https://github.com/oluwatosin17/Web-Scraping-Football-Matches-From-The-EPL-With-Python-/blob/main/Web%20Scraping%20Football%20Matches%20From%20The%20EPL%20.ipynb).
