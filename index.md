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
In the realm of aspirations and crescendos, Stanislas, a 20-year-old aspiring musician, embarked on a journey fueled by
a fervent passion for the film industry. Eager to hear his compositions resonate in Hollywood, he sought the guidance of 
the "LearningtheSecretsofData" (LSD) team, a group of Data Scientists on a mission to optimize choices for the budding 
composer.

## Music Genres
The LSD team’s investigation first turns to the rhythms and melodies that define cinema. They computed the histogram
of the most frequent music genres.

{% include Q1_histogram.html %}

For the sake of clarity, a chart is presented to facilitate readability, enabling Stanislas to filter movie genres based 
on their frequency in the analyzed dataset. By displaying the top 10 music genres (slider set to k=100), they discover a realm 
dominated by orchestral and classic soundtracks, the traditional heartbeat of film music genres.

<!--- old chart, redundant with the one below {% include Q1_pie.html %} --->
{% include Q1_slider.html %}

Yet, for Stanislas, who maybe yearns for something beyond the conventional, there lies an intriguing pathway - Bollywood. 
The vibrant and emotive sounds of Indian music offer a unique avenue, a divergence from the norm where his creativity 
could truly flourish.

{% include Q1_slider_without_soundtrack.html %}

## Expectations Based on Age

As the journey unfolds, age and time emerge as critical elements in a composer's voyage to success. The team finds that 
composers typically make their first movie appearance around the age of 34, though this number skews younger to about 31 
when outliers are set aside. Outliers can be seen as actors (or others people already in the industry) that produce 
music for a movie as a side job/activity and then can be considered apart.

{% include Q2_histogram.html %}

![Q2_plot1](/assets/img/Q2/c_age_first_appearance_years_Q2.png)

This additional plot paints a timeline for Stanislas, in average, a decade of growth and evolution before 
reaching the zenith of success, typically around the age of 42.

{% include Q2_2_histogram.html %}

![Q2_plot2](/assets/img/Q2/c_age_highest_revenue_years_Q2.png)

## Career Evolution

This trajectory, however, is as diverse as the composers themselves, each thread woven with personal stories, life's 
unpredictable twists, and the ever-present element of chance.

{% include Q3_number_of_movies_per_year.html %}

{% include Q3_box_office_revenue_per_year.html %}


## Place of Birth

The map of success doesn't just span genres and ages but also crosses borders and oceans. The USA and the UK emerge as 
the prominent birthplaces of top composers, with Germany, Japan, and India following.

{% include heat_map_world.html %}

## Gender

In this global tapestry, an unsettling truth comes to light – the stark scarcity of women in this domain.

![Q5_plot1](/assets/img/Q5/Q5_barplot.png)

{% include Q5_graph.html %}

## Personal Website

In the digital age, the significance of an online presence cannot be overstated, and Stanislas' path is no different. 
The LSD team uncovers a statistically significant correlation – composers with personal websites often find their work 
resonating more at the box office. It's important to clarify that there is no assertion of a causal relationship here; 
the team is simply highlighting the observed tendency between these two distinct features.

{% include Q6_boxplot.html %}

## Movie's Playlist VS Box Office

The melody of success isn't just in the composition but also in its reach. A positive correlation surfaces between the 
popularity of a movie's playlist and its box office revenue, adding another layer to Stanislas' strategy for success.

{% include Q7_histogram.html %}

{% include Q7_scatter.html %}

Pearsons correlation: **0.392**

{% include Q7_year_scatter.html %}

{% include Q7_correlation_heatmap.html %}