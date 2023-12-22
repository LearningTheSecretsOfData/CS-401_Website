---
layout: home
title: Stanislas Music Dream - Road to Hollywood !
subtitle: ADA CS-401 - Team LearningTheSecretsOfData
cover-img: "/assets/img/header_holy.png"
gh-repo: epfl-ada/ada-2023-project-learningthesecretsofdata
gh-badge: [ star, fork, follow ]
footer-extra: epfl.html
---

# Music Dream - Road to Hollywood!

Stanislas, a 20-year-old aspiring musician, embarked on a journey fueled by a fervent passion for the film industry.
Eager to hear his compositions resonate in Hollywood, he sought the guidance of the "LearningtheSecretsofData" (LSD)
team, a group of Data Scientists on a mission to optimize choices for the budding composer.

## Music Genres

The LSD team’s investigation first turns to the rhythms and melodies that define cinema by computing the histogram
of the most frequent music genres.

{% include Q1_histogram.html %}

For the sake of clarity, a chart is presented to facilitate readability, enabling Stanislas to filter movie genres based
on their frequency in the analyzed dataset. A slider is suggested to filter movie genres based on those with more than k
movies associated with them. By displaying the top 10 overall music genres (slider set to k=100), they discover a realm
dominated by orchestral and classic soundtracks, the traditional heartbeat of film music genres.
Also, if soundtrack genres, meaning the ones with "soundtrack" in the genre appellation are filtered, then we can see
other interesting genre used in movies. Stanislas, who maybe yearns for something beyond the conventional, can also find
an intriguing pathway - Bollywood. The vibrant and emotive sounds of Indian music offer a unique avenue, a divergence
from the norm where his creativity could truly flourish.

{% include Q1_slider.html %}

## Expectations Based on Age

As the journey unfolds, age and time emerge as critical elements in a composer's voyage to success. The team finds that
composers typically make their first movie appearance around the age of 34, though this number skews younger to about 31
when outliers are set aside. Outliers can be seen as actors (or others people already in the industry) that produce
music for a movie as a side job/activity and then can be considered apart.

{% include Q2_histogram.html %}

This additional plot paints a timeline for Stanislas, in average, a decade of growth and evolution before
reaching the zenith of success, typically around the age of 42.

{% include Q2_2_histogram.html %}

## Career Evolution

The following graphs depicts the career evolution of the 25 composers who have contributed in the highest number of movies.
This trajectory, however, is as diverse as the composers themselves, each thread woven with personal stories, life's unpredictable twists, and the ever-present element of chance. 
And yet, some trends appears for most of these composers: most of them begin by a period with fewer films projects early on, followed by a significant increase and a gradual decline over time.

{% include Q3_number_of_movies_per_year.html %}

Interestingly, a shared pattern emerges among the composers when examining the progression of box office revenue from the films they've been involved in. Indeed, a significant number of them achieve their revenue peak either during or immediately after the peak of their movie contributions, followed by a subsequent decline. This decline aligns with a decrease in the number of films they undertake which is a logical correlation in their evolving careers. For examplle, this is visible with John Williams.

{% include Q3_box_office_revenue_per_year.html %}

From this information, Stanny can draw some conclusions: He should work on the maximum number of movies possible while young. This would afford him the opportunity to ascend in his career by contributing to increasingly prominent films and then retire peacefully. While this isn't a foolproof and immutable recipe for success, it appears to be a common trend among top composers, at the very least!

## Place of Birth

The map of success doesn't just span genres and ages but also crosses borders and oceans. The USA and the UK emerge as
the prominent birthplaces of top composers, with Germany, Japan, and India following.

{% include heat_map_world.html %}

## Gender

In analyzing the design landscape, a disturbing fact emerges – a significant underrepresentation of women in this art form.

{% include Q5_bar.html %}

Despite the vibrant differences observed across genres, 
eras and places of birth in films, the gender diversity in 
movie composers remains a challenge.

{% include Q5_bars.html %}

Stanislas, as he makes his way in music, has a unique opportunity
to contribute to positive change. Recognizing the importance of
promoting gender diversity, it can actively seek solidarity and
develop policies that promote and elevate underrepresented 
voices.

## Personal Website

In the digital age, the significance of an online presence cannot be overstated, and Stanislas' path is no different.
The LSD team uncovers a statistically significant correlation – composers with personal websites often find their work
resonating more at the box office. It's important to clarify that there is no assertion of a causal relationship here;
the team is simply highlighting the observed tendency between these two distinct features.

{% include Q6_boxplot.html %}

*The 5 horizontal lines represent the minimal, lower quartile, median, 
upper quartile and maximal values (outliers put appart) respectively, from bottom to top. <br> The notch represents the 95% confidence interval*

## Movie's Playlist VS Box Office

In exploring the correlation between a movie's playlist popularity and 
its box office revenue, Stanislas finds another layer to his strategy 
for success. The resonance of a film's soundtrack, reflected in these 
visualizations, serves as a guiding note in his journey toward Hollywood.
Once again before Stanislas gets too hyped up thinking about how he will get famous simply by sharing his music on Spotify, the team of data scientists
re-explain to him the difference between correlation and causation.

{% include Q7_histogram.html %}

{% include Q7_scatter.html %}

{% include Q7_correlation_heatmap.html %}

## Conclusion

As the data story reaches its crescendo, Stanislas stands at a crossroads, armed with insights and a clearer vision for
his journey. Orchestral and classic soundtracks beckon as his chosen genre, a personal website and a Spotify account as his digital banner,
and an
unwavering commitment to fostering gender diversity in an industry where it's long overdue. His path is his own, unique
and unpredictable, shaped by personal choices, and a touch of fortune.

Stanislas' story is more than a tale of music and movies; it's a narrative of how data can illuminate paths previously
unseen and how one individual, fueled by passion and guided by information, can aspire to not just succeed but also to
inspire change.
