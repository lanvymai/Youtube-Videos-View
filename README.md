# Exploring Factors Influencing Youtube Views

This project aims to analyze various factors that influence the number of views on YouTube videos using data analysis and statistical techniques.

## Tools Used

- Python
- GitHub
- MacOS Terminal
- Multivariate Regression
- Ordinary Least Square

## Project Overview

This data science project explores the relationships between different variables and YouTube video views. The analysis includes handling missing values, correlation analysis, and various visualizations to understand the factors affecting video popularity.

# The dataset

In this project, I used [Kaggle Data Science Youtube Video Meta Data](https://www.kaggle.com/themlphdstudent/data-science-youtube-video-meta-data) collected by The ML PhD Student
> ## Overview of the dataset
> - 44,261 Youtube videos, 60 channels
> - Time series data from 2006-2020
> - 21 variables in total
> - Data available for Channels, View, Comments, Duration in seconds, Likes & Dislikes, Video Quality, and Caption, etc.
> - Four unique categories of interest


## Key Visualizations

1. Correlation matrix

![correlation matrix](https://github.com/user-attachments/assets/bc5faa82-1ff5-4e2e-bb07-5ffeeb714006)


2. Linear model plots of likes to views for selected video categories

![LM plot likes to view (4 categories of interest)](https://github.com/user-attachments/assets/ad7cbb3d-3f71-4ef1-816c-5582049579ef)


3. Linear model plots of comments to views for selected video categories

![LM plot of comment to view](https://github.com/user-attachments/assets/6e8ac944-044c-4808-b13a-d672fd361ea5)


4. Relational plots of views, comments, and video quality for selected categories

![relational plot of view comment quality](https://github.com/user-attachments/assets/d6f6c83b-99f0-4fe7-8219-7fac807a59c3)


5. Relational plots of views, likes, and video caption for selected categories

![relplot of view like caption](https://github.com/user-attachments/assets/26cf2389-e4f0-4d3b-a87a-38a9031d3799)


6. Count of video categories in the dataset

![count of categories](https://github.com/user-attachments/assets/ad6f458b-45cf-4233-b456-75c01c9dcd43)


7. View distribution across all video categories

![view dist](https://github.com/user-attachments/assets/abfd0707-df42-4705-bc98-af89d9009357)


8. Distribution of views, comments, likes, and duration variables

![comment like duration dist](https://github.com/user-attachments/assets/44604457-9a30-4dfe-aaff-18afd9c7b70a)


9. Distribution of log-transformed views, comments, likes, and duration variables

![log transform](https://github.com/user-attachments/assets/bd1727d8-4ad4-4c27-9f0e-e8e1514709d6)


## Data Preprocessing

The project involved handling missing values in the dataset.

![missing value](https://github.com/user-attachments/assets/b4635aa9-a179-4ea2-82ab-3dd61286597f)

After imputing missing values:

![after handling missing value](https://github.com/user-attachments/assets/5822e0bc-b872-488c-8046-de74d4d491ac)


## Analysis Highlights

- Exploration of relationships between likes, comments, and views for different video categories
- Investigation of the impact of video quality and captions on view counts
- Examination of view distribution across various video categories
- Analysis of the distribution of key variables (views, comments, likes, duration) and their log-transformed versions

## Results

The project provides insights into the factors that influence YouTube video views through various statistical analyses and visualizations. 

> Having a video in standard quality will increase views. 
> Videos with low view have captions for videos will decrease views.
> Educational videos attract the most views in our model
> Shorter videos tend to attract more views
> Percentage increases in likes will increase views
> Less comments correlated with videos having more views


## Future Work

### Limitation of dataset
- Missing values
- Missing definitions of categories
- Multicollinearity and dislikes
- Overrepresentation of categories
- Overrepresentation of quality
- Few number of channels

### Potential areas for future exploration
- Deeper analysis of specific video categories
- Incorporation of additional variables that may affect view counts
- Time-series analysis of view trends

## Contributing

Contributions to this project are welcome. Please feel free to fork the repository, make changes, and submit pull requests.

## Acknowledgments

This project was completed as the final project for ECON 275: Business Analytics Beloit College 2021. Special thanks to the course instructors Prof Disha Shende.

For more detailed information and to view the full presentation, visit [presentation](https://docs.google.com/presentation/d/10k9VQpcAs0_wi2CeLyNgpXJ8jdllNvID/edit#slide=id.p19)
