# Investigating Netflix Movies

## Project Overview

Netflix has grown from a DVD rental service founded in 1997 into one of the world’s leading entertainment platforms. With thousands of titles available, its catalog offers rich opportunities for data exploration.

This project focuses on analyzing Netflix movies from the **1990s**, a decade known for iconic films, cultural shifts, and memorable storytelling. The goal was to uncover patterns in movie durations and examine the presence of short action films during that era.

---

## Objectives

The analysis aimed to answer two key questions:

* What was the **most common movie duration** for Netflix movies released in the 1990s?
* How many **Action movies shorter than 90 minutes** were released during that period?

---

## Dataset Information

The dataset used was `netflix_data.csv`, containing information such as:

* Show ID
* Type (Movie / TV Show)
* Title
* Director
* Cast
* Country
* Date Added
* Release Year
* Duration
* Description
* Genre

---

## Tools & Technologies

* **Python**
* **Pandas** for data cleaning and analysis
* **Matplotlib** for visualization
* **Jupyter Notebook**

---

## Analysis Process

The workflow included:

1. Importing and loading the dataset using Pandas
2. Filtering records to include only **Movies**
3. Selecting movies released between **1990 and 1999**
4. Converting duration values into numeric format
5. Calculating the most frequent runtime using mode
6. Filtering Action movies and counting titles under 90 minutes
7. Visualizing movie duration distribution using a histogram

---

## Key Findings

### Most Common Duration of 1990s Movies

**94 minutes**

This suggests that many movies in the 1990s followed a compact runtime structure, likely designed for stronger pacing and broader audience appeal.

### Short Action Movies Under 90 Minutes

**7 movies**

This indicates that while action films were popular, shorter runtimes were less common, as the genre often requires longer screen time for plot development and action sequences.

---

## Business Insight

The nostalgic entertainment market can benefit from these findings:

* **94-minute runtimes** may resonate well with audiences seeking authentic 1990s-style films.
* Shorter action films were rare, creating an opportunity for modern producers to reintroduce fast-paced retro action content.
* Studios creating nostalgic content can use this runtime benchmark to improve audience engagement and retention.

---

## Visualization

A histogram was created to show the distribution of movie durations in the 1990s, helping reveal runtime concentration trends.

---

## Project Outcome

```python
most_frequent_movies_90s_duration = 94
short_action_movies = 7
```

---

## Repository Structure

```bash
Investigating-Netflix-Movies/
│── netflix_data.csv
│── netflix_analysis.ipynb
│── README.md
```

---

## Author

Jeremiah Kehinde

