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
1. Used the ```INSERT INTO``` command to insert an additional list item into the database.
2. Used THE  ```SELECT SUM() FROM``` to query how many total minutes the items on my list would take to complete. 

---
### Exploratory Data Analysis
---

EDA involved exploring the movie data to answer key questions such as:
1. How many minutes should I allocate to completing the tasks on my list?

---
### Data Analysis
---

Interesting code/features worked with:

```sql
SELECT SUM(minutes) FROM todo_list;
```

```sql
INSERT INTO todo_list VALUES (4, "Khan Academy Challenge", 10);
```

---
### Results or Findings
---

The analysis results are summarized as follows:
- The results revealed that it will take me around 75 minutes to complete all of the items in my todo list.

---
### Insights
---

It took me some time to figure out the request oder. Still don't think I fully understand the order but know I'll get the hang of it with more practice.

---
### Recommendations
---

- Could perform a query into listing the tasks in the order of descending time commitment.

---
### Limitations
---

There were no limitations in this database. In the future I will use this section to detail any outliers or adjustments I had to make to the data to protect the accuracy of analysis I'm working to achieve.

---
### References or Resources
---

1. [Khan Academy](https://www.khanacademy.org/computing/computer-programming/sql/sql-basics/pc/challenge-todo-list-database-stats)
