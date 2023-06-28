# Data Analysis and Visualization Covid-19

This repository contains code for performing data analysis and generating visualizations using the provided dataset. The code demonstrates various techniques for handling NaN values, calculating statistics, and creating sophisticated visualizations.

## Dataset

The dataset used for analysis contains the following columns:

- user_name: Name of the user (non-null object)
- user_location: Location of the user (non-null object)
- user_description: Description of the user (non-null object)
- user_created: Date of user creation (non-null object)
- user_followers: Number of user followers (non-null int64)
- user_friends: Number of user friends (non-null int64)
- user_favourites: Number of user favourites (non-null int64)
- user_verified: User verification status (non-null bool)
- date: Date of the tweet (non-null object)
- text: Tweet text (non-null object)
- hashtags: Hashtags used in the tweet (non-null object)
- source: Source of the tweet (non-null object)
- retweets: Number of retweets (non-null int64)
- favorites: Number of favorites (non-null int64)
- is_retweet: Whether the tweet is a retweet (non-null bool)
- sentiments: Sentiment analysis of the tweet (non-null object)
- Positive Sentiment: Positive sentiment score (non-null float64)
- Neutral Sentiment: Neutral sentiment score (non-null float64)
- Negative Sentiment: Negative sentiment score (non-null float64)

## Code Description

- `covid19.ipynb`: Jupyter Notebook containing the code for data analysis and visualization.
- `vaccination_tweets.csv`: Dataset file to be used for the analysis. Replace with your actual dataset file.

## Dependencies

The following Python libraries are required to run the code:

- pandas
- numpy
- matplotlib
- seaborn

Install the dependencies using the following command:

```
pip install pandas numpy matplotlib seaborn
```


## Instructions

1. Clone this repository or download the files.
2. Replace `your_dataset.csv` with your actual dataset file, ensuring it has the same structure as described above.
3. Open and run `covid19.ipynb` in Jupyter Notebook or any compatible environment.
4. Follow the code comments to understand the steps and modify the code as needed.
5. Explore the data analysis and visualizations generated by the code.

Feel free to modify the code and adapt it to suit your specific requirements and dataset.

For any questions or issues, please contact [saqibiqbal27772@gmail.com](mailto:saqibiqbal27772@gmail.com).

