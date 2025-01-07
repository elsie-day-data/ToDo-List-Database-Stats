# Box Office Hits SQL Database

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Preparation](#data-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results Or Findings](#results-or-findings)
- [Insights](#insights)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References or Resources](#references-or-resources)

---
### Project Overview
---

This data analysis project aims to 1) insert an additional item in the "to do" list, and 2) obtain the sum of the minutes it will take to do all of the items in the list.

<img width="1112" alt="Screenshot 2025-01-06 at 7 24 22 PM" src="https://github.com/user-attachments/assets/ad7ddf84-3461-4990-b0ba-c08b04a3575f" />

---
### Data Sources
---

ToDo List Data: The primary dataset used for this was Khan Academy data.

---
### Tools
---

- SQL Lite

---
### Data Preparation
---
In the initial data preparation phase, I performed the following tasks:
1. Used the ```SELECT * FROM movies;``` command to pull and review all the data in the "movies" database.

---
### Exploratory Data Analysis
---

EDA involved exploring the movie data to answer key questions such as:
1. Are there any movies that are from the year 2000 or greater?
2. What is the list if we sort them by the year?

---
### Data Analysis
---

Interesting code/features worked with:

```sql
SELECT * FROM movies WHERE release_year > 2000 ORDER BY release_year;
```

---
### Results or Findings
---

The analysis results are summarized as follows:
- The results revealed that there were three movies in the list that were from the year 2000 or greater.
- The results showed that the first movie to be released from 2000 and beyond was Shrek 2 (2004 release). 

---
### Insights
---

It was interesting that building this data set required three phases of
1. I first attempted to just do a "SELECT * movies" query but realized that I needed to first tell the syntax where to select "movies" from.

``` SELECT * movies;``` changed to ``` SELECT * FROM movies;```

---
### Recommendations
---

- Could be worth adding ratings and categories to the dataset and explore if there is any correlation between ratings and movie categories.

---
### Limitations
---

There were no limitations in this database. In the future I will use this section to detail any outliers or adjustments I had to make to the data to protect the accuracy of analysis I'm working to achieve.

---
### References or Resources
---

1. [Khan Academy](https://www.khanacademy.org/computing/computer-programming/sql/sql-basics/pc/challenge-box-office-hits-database)
