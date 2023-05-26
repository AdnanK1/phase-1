# Exploratory data analysis: Generate insight for Microsoft

## Introduction

Microsoft Corporation is a multinational technology company headquartered in Redmond, Washington, United States. It was founded by Bill Gates and Paul Allen in 1975. Microsoft is known for developing, manufacturing, licensing, and supporting a wide range of software products, hardware devices, and services.

Microsoft's primary product is the Microsoft Windows operating system, which is widely used in personal computers around the world. Windows has evolved over the years and now powers various devices such as desktops, laptops, tablets, and smartphones. Additionally, Microsoft offers a suite of productivity software, including the widely used Microsoft Office suite, which consists of applications like Word, Excel, PowerPoint, and Outlook.

## Problem Statement

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

By analyzing the prevailing box office performance, we can gain valuable insights into audience preferences and tailor our movie production strategy accordingly. These insights will guide decision-making processes, ensuring that Microsoft's movie studio creates films with a higher likelihood of commercial success.

## Specific Objective

The objective is to conduct exploratory data analysis on the `im.db` database in order to provide the company with statistical data. This analysis aims to offer valuable insights on which genres the studio should focus on to enhance their performance and receive favorable ratings. By examining the data and applying statistical techniques, we can provide the studio with meaningful recommendations regarding the genres that have the potential to improve their overall quality and attract positive audience reception.

## Data Understanding

The data being used is from the `im.db` database in which we are using two tables. Which are :

    * movie_basics
    * movie_ratings

The "movie_basics" table comprises 146,144 rows and includes six columns. It provides information about various movie attributes such as movie_id, primary_title and original_title, start_year, runtime_minutes and genre.

On the other hand, the "movie_ratings" table contains 73,856 rows and consists of three columns. This table contains data related to the ratings received by the movies, including average rating, number of votes, and movie ID.

By leveraging the data from these two tables, we can gain insights into the movie attributes and ratings, allowing for comprehensive analysis and informed decision-making in the movie industry.

## Conclusion

- Based on the analysis, it is evident that documentaries, biographies, music-related films, and sports-themed movies have achieved the highest average ratings. These genres have resonated well with audiences, reflecting their appreciation for factual storytelling, real-life narratives, and engaging musical and sports content.

- Conversely, horror and science fiction (sci-fi) films have obtained the lowest average ratings. This indicates that these genres may not have resonated as strongly with viewers, suggesting a potential area for improvement in terms of audience reception and satisfaction.

- These findings provide valuable insights for the studio, highlighting the genres that have a higher likelihood of receiving positive ratings and garnering audience acclaim. By leveraging these insights, the studio can focus on producing more content in the genres that have proven to be well-received, while also considering ways to enhance the quality and appeal of horror and sci-fi films to improve their ratings and audience reception.

## Recommendation

Based on the analysis, it is recommended that the new Microsoft movie studio focuses on genres such as documentaries, biographies, music, and sports. These genres have consistently received high ratings and have resonated well with audiences. By capitalizing on the audience's preference for factual storytelling, real-life narratives, and engaging content related to music and sports, the studio can increase the likelihood of positive reception and audience satisfaction.

In contrast, the analysis indicates that horror and sci-fi genres have obtained lower ratings. Therefore, it would be prudent for the Microsoft studio to prioritize genres that have demonstrated a higher potential for success, rather than investing heavily in horror or sci-fi films, which may face more challenges in terms of audience reception and satisfaction.

By aligning the studio's content production strategy with genres that have a proven track record of positive ratings, Microsoft can position itself to deliver compelling and well-received films, enhancing its chances of success in the competitive movie industry.
