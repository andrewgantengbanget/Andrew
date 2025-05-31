# Successful Educations: Data Science Final Project

This project explores the academic backgrounds of 108 globally recognized individuals using a dataset from Kaggle:  
https://www.kaggle.com/datasets/adilshamim8/educational-backgrounds-of-successful-people

The goal is to uncover trends in degrees, university prestige, and GPA, and how they may relate to career success. The dataset includes attributes such as name, profession, degree, institution, country, university global ranking, GPA (or equivalent), and academic awards.

## Data Preprocessing

To ensure accurate analysis, the dataset was cleaned and preprocessed. University rankings and GPA values were converted to numeric types. Missing values in key fields such as Degree, Profession, and Country were dropped. Additional filtering was done depending on the objective (e.g., removing rows with missing GPA or ranking). Rankings were also normalized using MinMaxScaler for correlation analysis.

## Objective 1: Degree Distribution Across Professions

We examined how different academic degrees are distributed across professions. By grouping and counting degree-profession combinations, we found that Bachelor's degrees in Business and Entrepreneurship are the most frequent. Master's degrees and MBAs are also common, particularly among entrepreneurs and tech executives. Some outliers, like law degrees and dropouts, also appear, highlighting that success is not limited to conventional paths.

## Objective 2: Top Countries by Average University Ranking

This analysis focused on the average global ranking of universities attended by successful people, grouped by country. The results show that the United States and Canada have the lowest (best) average rankings, followed by France, the UK, and Germany. This suggests that graduates from top-ranked institutions in North America and parts of Europe are highly represented among successful individuals.

## Objective 3: GPA vs University Ranking

We investigated whether students from higher-ranked universities tend to have higher GPAs. After normalizing rankings and plotting against GPA, the correlation analysis showed a weak negative relationship (Pearson coefficient: -0.21). This implies that although individuals from better-ranked universities may have slightly higher GPAs, the relationship is not strong. Academic performance is influenced by many factors beyond institutional prestige.

## Conclusion

This project shows that while academic degrees and university reputation do play roles in the success of individuals, they are not definitive indicators. Most successful people hold at least a bachelor's or master’s degree, often from top-ranked institutions, but success also occurs outside these norms. There is only a slight connection between GPA and university ranking, suggesting that personal achievement depends on more than academics alone.
