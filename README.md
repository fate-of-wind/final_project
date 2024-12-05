# Final Project

# Impact of NBA Games on Chicago Traffic Accidents Analysis
## Dataset:
NBA_in_Chicago_17_24.csv: direct use my csv in git (7 KB) or create by GetDatasetFinal.ipynb

Traffic_Crashes.csv: Download from https://drive.google.com/file/d/13XZFhgBVqwst4xCnaSkaKy8QdGXDPj1f/view?usp=drive_link (462.9 MB)
## Project Proposal: 
### Goal: 
* Analyze the correlation between Chicago Bulls home games and traffic accident rates in Chicago
* Determine if there are specific patterns in accident locations near the United Center
### What I’ll do: 
* I'll collect all the necessary data, including Chicago traffic accidents, NBA game schedules in Chicago
* I’ll analyze weather data(rain with precipitation) for different days so I can control confounding variables.
* I'll additionally analyze accidents near location of NBA game - United Center(arena of Chicago Bulls)
* I’ll calculate baseline number of accidents per day for different days and compare these them during game days vs non-game days.
* I’ll generate box plot showing accident per day during game days vs non-game days.
* I’ll produce statistical summaries and use techniques (two-sample t test, effect size with Cohen's d, confidence interval) to analyze my statement.
* I’ll use machine learning techniques (such as LSTM, XGBoost, …)to predict the trend of traffic accident rates and find out the relationship between NBA games and Chicago traffic accidents rate.
* I'll analyze the feature importance of machine learning models to determine the significance of NBA Game Day as a factor in crash numbers.

## Project Execution Plan:
* By the end of week 4, 
    * I will have collected all the necessary data, including Chicago traffic accidents, NBA game schedules in Chicago (especially focusing on the Chicago Bulls), and weather data.
    * I will address any missing data or inconsistencies.
* By the end of week 5, 
    * I will have conducted initial exploratory data analysis, examining overall traffic accident trends, and compare number of accidents per day on game days vs non-game days.
    * I will also create initial time series plots to visualize trends in accident rates over time.
* By the end of week 6, 
    * I will have implemented controls for confounding variables like weather conditions.
    * I will calculate baseline accident rates under different weather conditions (e.g., rain vs no rain) and compare them to number of accidents per day on game days to account for potential confounding effects.
* By the end of week 7, 
    * I will have performed spatial analysis, analyzing accidents near United Center(within 2.5km)
    * I will assess whether there is clustering or unusual patterns on game days.
    * I will produce statistical summaries using significance tests (two-sample t test, effect size with Cohen's d, confidence interval) to analyze correlations.
* By the end of week 8, 
    * I will have built and trained machine learning models (e.g., LSTM, XGBoost) to predict accident rates based on historical data, including game schedules, weather conditions, and other relevant features.
    * I will evaluate the models' performance using appropriate metrics such as accuracy, and fine-tune them.
    * I will analyze the feature importance of machine learning models to determine the significance of NBA Game Day as a factor in crash numbers.
* Finally, 
    * I will have summarized all my findings and adjusted the layout of my final report to make it more readable.
    * I will have prepared a presentation to showcase my analysis and conclusions on the relationship between NBA games and traffic accident rates in Chicago.