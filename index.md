---
layout: home
title: Stanislas Music Dream - Road to Hollywood ! 
subtitle: ADA CS-401 - Team LearningTheSecretsOfData
cover-img: "/assets/img/header_holy.png"
gh-repo: epfl-ada/ada-2023-project-learningthesecretsofdata
gh-badge: [star, fork, follow]
footer-extra: epfl.html
---

# Music Dream - Road to Hollywood!
A Data-Driven Journey of Soundtrack Composer Stanislas



## Q1: Which are the most frequent music genre appearing in movies ?
{% include Q1_histogram.html %}

{% include Q1_pie.html %}

{% include Q1_slider.html %}

{% include Q1_slider_without_soundtrack.html %}


## Q2: What is the average composer's age at their : 
- ### first movie appearance ?
The average age of the composer at his first movie is:
 **34.198 years** or
 **12490.663 days**
{% include Q2_histogram.html %}

![Q2_plot1](/assets/img/Q2/c_age_first_appearance_years_Q2.png)

- ### biggest box office revenue ?
The average age of the composer at his highest box office revenue is:
 **41.891 years** or **15300.559 days**

{% include Q2_2_histogram.html %}

![Q2_plot2](/assets/img/Q2/c_age_highest_revenue_years_Q2.png)

## Q3: How the top composers' career progress over the years ?

![Q3_plot1](/assets/img/Q3/Q3_barplot.png)

![Q3_plot2](/assets/img/Q3/Q3_lineplot.png)

![Q3_plot3](/assets/img/Q3/Q3_lineplot_revenue.png)


## Q4: Where do composers come from ?

{% include heat_map_world.html %}

## Q5: Does composer's gender matter ?

![Q5_plot1](/assets/img/Q5/Q5_barplot.png)

![Q5_plot2](/assets/img/Q5/Q5_barplot_stacked.png)

## Q6: Does having a personal website correlate with the composers' success ?

![Q6_plot1](/assets/img/Q6/Q6_boxplot.png)

## Q7: Is there a correlation between box office revenue and movie's playlist popularity ?

{% include Q7_histogram.html %}

{% include Q7_scatter.html %}

Pearsons correlation: **0.392**

{% include Q7_year_scatter.html %}

{% include Q7_correlation_heatmap.html %}