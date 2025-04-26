# 🎬 Netflix-Movie-Data-Analysis

# 📊 Project Overview
This project explores a movie dataset consisting of 9,827 movies and 9 features. Through exploratory data analysis (EDA) and preprocessing, we extract insights about genre distributions, popularity patterns, and voter preferences.

The analysis identifies key trends that could help production companies, streaming services, or content strategists better understand audience tastes.

# 🔥 Project Workflow
Dataset Inspection

9,827 rows × 9 columns

No missing (NaN) or duplicate values detected

Data Preprocessing

Dropped non-essential columns: Overview, Original_Language, and Poster_Url

Converted Release_Date to proper datetime format

Cleaned Genre column (handled comma-separated values and whitespace)

Detected outliers in Popularity for further treatment

Categorized Vote_Average for better analytical grouping

Exploratory Data Analysis

Genre frequency and voting distribution

Identified movies with highest and lowest popularity

Analyzed genre influence on popularity and votes

#📈 Key Insights and Findings
Most Frequent Genre:

Drama is the most frequent genre, appearing in more than 14% of all movies across 19 genres.

Highest Votes by Genre:

Approximately 25.5% of the dataset (6,520 movies) received significant popular votes.

Drama again ranked first, securing over 18.5% of these popular entries.

Highest Popularity Movie:

Spider-Man: No Way Home achieved the highest popularity.

Genres: Action, Adventure, Science Fiction.

Lowest Popularity Movie:

The United States Thread recorded the lowest popularity.

Genres: Music, Drama, War, Science Fiction, History.

# ⚙️Data Preprocessing Summary
Dropped irrelevant columns (Overview, Original_Language, Poster_Url).

Casted Release_Date to datetime type.

Split and cleaned the Genre column for accurate analysis.

Identified and flagged outliers in the Popularity feature.

Categorized Vote_Average into bins: Low (0–4.9), Medium (5.0–7.9), High (8.0–10).

# 🛠Technologies Used
Python (Pandas, NumPy)

Matplotlib and Seaborn for visualization

Jupyter Notebook

# 📋Conclusion 
🔹Analyzed popularity distribution across 9,827 movies and found that Drama received the highest fan engagement, representing over 18.5% of popular titles.

🔹Identified “Spider-Man: No Way Home” as the most popular movie, classified under Action, Adventure, and Science Fiction, while “The United States Thread” had the lowest popularity, spanning five niche genres.

🔹Used genre-wise vote analysis to derive trends in viewer preferences and highlight extremes in popularity for strategic insight.

# THANK YOU
