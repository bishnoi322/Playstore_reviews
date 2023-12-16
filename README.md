Link to the article:
https://medium.com/@bishnoi.kanchan4141/google-playstore-app-reviews-2eeda2a1dbfb
**Finding dataset:**
In embarking on this project, my objective was to capture the immediate impact of public response on product sales, and what better metric to gauge this than through online reviews, where people's emotions are succinctly encapsulated in the form of ratings. I specifically opted for app reviews as they offer a straightforward dataset, influenced by a limited number of factors and devoid of any retailer involvement, thereby providing a clear and focused perspective.
**Dataset downloaded from kaggleAnalytical questions to look for:**
Data analytics questions for a Google Play Store apps dataset can help you uncover insights and make informed decisions about app performance, user behavior, and market trends. Here are some sample questions you can explore using such a dataset:
**App Popularity and Ratings:** a. What is the distribution of app ratings on the Play Store? b. Which categories have the highest average ratings? c. Do higher-rated apps tend to have more downloads?
**App Categories:** a. What are the most popular app categories on the Play Store in terms of downloads and user ratings?
Depicts correlation between the size of app and it's ratingUser Reviews: a. What are the most common words or phrases used in user reviews for highly-rated apps? b. Is there a correlation between the length of reviews and app ratings? c. How do user sentiment and the sentiment expressed in reviews relate to app success?
**App Size and Compatibility:** a. How does the app's file size affect its download and rating metrics? b. What is the distribution of Android OS versions required by different apps? c. Do apps with broader compatibility tend to perform better?
**Downloads and Installs:** a. What is the distribution of app downloads and installs? b. Do apps with more installs also have a higher rating? c. How has the number of installs changed over time?
These questions can serve as a starting point for data analysis. Depending on the specific dataset and my goals, I may need to tailor and expand these questions to gain deeper insights into the performance and trends within the Google Play Store ecosystem.
**Cleaning the data:**
One prevalent challenge encountered in datasets of this nature pertains to irregularities stemming from the presence of operators within columns. For instance, in the "installs" column, numerical values are often represented as ranges, such as "10,000+," introducing ambiguity that can lead to misinterpretation and potentially yield inaccurate results. Additionally, the dataset may exhibit issues related to redundant or null values, further complicating analytical processes. The mitigation of these challenges necessitates thorough data cleaning procedures, thereby enhancing the dataset's integrity and rendering it more amenable to subsequent analysis. One way to resolve an issue is displayed in the following code using the pandas library which looks for and subsequently drops the missing value in columns "Rating" and "Installs":
**Analytical process and Results:**
Following the data cleaning process, the subsequent phase involves the systematic pursuit of answers to the previously posed inquiries, the resolution of which is eagerly anticipated. The acquired results are meticulously sought and subsequently elucidated through visual representations, predominantly in the form of graphs, facilitating a comprehensive understanding for stakeholders.
1.The predominant distribution of app ratings falls within the range of 4.0 to 4.5, indicating a common trend towards moderately positive user evaluations.
2. Apps within the categories of education, art and design, books and reference, personalization, parenting, and games consistently achieve top ratings, emphasizing the significance of content and functionality in these genres.
3. A linear correlation between app ratings and downloads persists until a specific rating threshold, beyond which the trend plateaus. Notably, apps rated between 4.5 to 4.8 demonstrate the highest download counts, suggesting a sweet spot for user preferences. To illustrate, the inquiry, "Do higher-rated apps tend to have more downloads?" necessitates establishing a correlation between the "Ratings" and "Downloads" columns. This correlation is effectively visualized through the deployment of a scatter-plot graph. The outcomes derived from our dataset are succinctly summarized as follows:
The graphical representation elucidates a direct correlation between app ratings and the volume of app installations, with the range of 4.0 to 4.8 garnering the highest number of installs. This observation offers insights into the average user's response, highlighting a negative correlation wherein lower ratings are indicative of a less favorable user experience. Conversely, ratings exceeding 4.9 elicit a sense of mistrust and raise questions about the reliability of these exceptionally high ratings. Consequently, the 4.0 to 4.8 rating range emerges as the most influential factor in driving app installations, reflecting a balance between user satisfaction and perceived credibility.To know more visit my github page: https//github.com/bishnoi322
4.The analysis of app sizes versus installations reveals a declining trend, indicating that smaller-sized apps tend to have higher download rates, reflecting user preferences for efficiency and resource optimization.
5. Examining the relationship between app ratings and installations reveals a median curve, implying that apps with moderately-sized file dimensions tend to receive the highest user ratings.
6. In the context of the top categories, the Tools category emerges as the leader in app downloads, followed by social, productivity, communication, and games. This highlights the dominant influence of utility-oriented applications in driving overall download figures within the app marketplace.
**Recommendations:**
1.Enhance User Experience within the 4.0 to 4.5 Range:
Stakeholders should focus on refining and enhancing user experiences for apps falling within the 4.0 to 4.5 rating range. Identifying and addressing common user concerns can lead to more positive evaluations.

2. Invest in Content and Functionality for Top Categories:
Given the consistently high ratings in education, art and design, books and reference, personalization, parenting, and games, stakeholders should prioritize investments in content quality and functionality within these categories to maintain and potentially increase user satisfaction.

3. Optimize App Features in the 4.5 to 4.8 Range:
Recognizing the plateauing trend in downloads beyond a 4.8 rating, stakeholders are advised to carefully optimize app features within the 4.5 to 4.8 range to align with user preferences. This could involve incorporating additional functionalities or addressing specific user needs to enhance overall appeal.

4. Prioritize Efficiency in App Sizes:
Considering the declining trend in app sizes versus installations, stakeholders should prioritize optimizing app sizes to align with user preferences for efficiency and resource optimization. This may involve streamlining features, minimizing unnecessary elements, and adopting efficient coding practices.

5. Focus on Moderate-Sized Apps for Higher Ratings:
Acknowledging the median curve in the relationship between app ratings and installations, stakeholders should aim for moderate-sized apps, as they tend to receive the highest user ratings. Balancing features with efficient file sizes can contribute to positive user perceptions.

6. Leverage the Dominance of Utility-Oriented Apps:
Given the dominance of the Tools category in app downloads, stakeholders are encouraged to explore opportunities within utility-oriented applications. Developing and promoting apps that serve practical purposes, enhance productivity, and facilitate communication could lead to increased market share and user engagement.

These recommendations are tailored to leverage the identified trends and preferences, providing stakeholders with strategic insights to refine and improve their products in alignment with user expectations and market dynamics.
**Tools and Technology Used :**
Pandas library
Numpy library
Kaggle
Seaborn library
