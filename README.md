#YouTube Watch History Analysis


YouTube has become an integral part of my daily life, serving as a source of entertainment, education, and inspiration. From tutorials to entertainment, it offers endless content for both productivity and relaxation. This project explores my YouTube watch history to uncover meaningful patterns, validate hypotheses, and gain actionable insights into my viewing behavior.

##Motivation
My interests span across a diverse range of topics, and my watch history reflects this variety. By analyzing my data, I aim to:

- Understand how my preferences translate into viewing habits.
- Identify time-based viewing patterns.
- Make more intentional choices about content consumption.
##Interests and Categories
Some of the key content categories I enjoy include:

- Gaming: Videos related to games, esports, and live streams are a significant part of my viewing activity.
- Music: I explore a variety of hip-hop and electronic music, often diving into DJ sets and live performances.
- Sports: Highlights, updates, and commentary on NBA and football games keep me informed and entertained.
- Technology: Deep dives into the latest advancements, product reviews, and tutorials fuel my curiosity.
- Psychology: Exploring videos on self-improvement, human behavior, and mental health fascinates me.
- Food: Cooking tutorials, recipe videos, and food reviews inspire my culinary experiments.
##Project Objectives
This project combines personal interest and data science techniques to analyze my YouTube watch history and answer key questions:

- What are my most-watched genres?
Discover the content categories that dominate my screen time.

- How does my viewing behavior vary across time?
Identify patterns by the hour of the day, day of the week, and working vs. non-working hours.

- What trends emerge in my preferences?
Understand how my preferences evolve over time and how specific channels influence my interests.
##Dataset
The dataset is extracted from my personal YouTube watch history using Google Takeout and contains:

- Video Titles: The names of the videos I have watched.
- Timestamps: The exact date and time of each video.
- Categories: Content types, such as music, gaming, education, or entertainment.
- Channels: Information on the content creators and their influence on my preferences.
  
##Data Preprocessing
- Parsed timestamps to extract key information such as the hour of the day and day of the week.
- Categorized videos into predefined content genres.
- Cleaned data by removing duplicates and irrelevant entries.
##Analysis Plan
###Exploratory Data Analysis (EDA)
- Content Preferences:
Identify dominant categories (e.g., Gaming, Music) and influential channels.

- Time-Based Trends:
Analyze activity by hour, day, and working vs. non-working hours.

- Viewing Patterns:
Uncover trends in weekday vs. weekend activity and peak times of viewing.

##Visualizations
- Bar Charts: Highlight the distribution of categories and hourly activity.
- Heatmaps: Show time-based patterns for content consumption.
- Word Clouds: Represent frequently watched video titles and themes.
  
##Hypothesis Validation
The hypothesis tested in this project is:
"I watch more YouTube outside of regular 9–17 working hours, and usually close to midnight."
Through time-based analysis, the data confirms that most of my viewing occurs during non-working hours, with significant peaks close to midnight.

##Key Insights
- Content Preferences: Music, Gaming, and Entertainment dominate my watch history. Channels like Crossover Talks and Boiler Room significantly influence my viewing.
- Time Patterns: Most videos are watched during non-working hours, peaking between 9 PM and midnight.
- Weekday vs. Weekend Trends: Higher activity on weekends correlates with more free time.
##Future Work
- Dataset Expansion:
Include data from other platforms like Netflix and Spotify for a holistic view of digital consumption.
- Category-Specific Insights:
Dive deeper into Music genres, Gaming preferences, and specific creators.
- Predictive Modeling:
Use machine learning techniques to predict future viewing preferences based on past trends.
- Content Balance Analysis:
Investigate the balance between entertainment and educational content to optimize screen time for personal growth.
##Conclusion
This analysis not only validates my viewing patterns but also provides actionable insights for intentional content consumption. It demonstrates the value of data science in uncovering trends in everyday behavior and offers a foundation for making better decisions about digital habits.
