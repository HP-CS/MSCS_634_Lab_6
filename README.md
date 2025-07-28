1. Purpose
The purpose of this lab is to apply association rule mining techniques using the Apriori and FP-Growth algorithms to discover hidden patterns in transactional data. By exploring real-world datasets, this lab demonstrates how frequent itemsets and association rules can be identified and interpreted for meaningful business insights.

2. Key Insights
- The most frequently purchased items were successfully visualized using bar plots.
- Apriori and FP-Growth algorithms yielded similar frequent itemsets, but FP-Growth executed significantly faster.
- Association rules with high confidence and lift revealed strong item affinities. For example, customers who bought item A were highly likely to also buy item B.
- Seaborn visualizations such as heatmaps and scatter plots helped interpret item co-occurrence and rule strength effectively.

3. Challenges & Decisions
- Data cleaning was essential, especially removing null values and irrelevant columns from the dataset.
- Choosing the right support and confidence thresholds required experimentation to balance rule quantity and quality.
- Visualizing rule strength with Seaborn required reshaping data into an interpretable format.
- FP-Growth proved more scalable for larger datasets and was less computationally intensive than Apriori.

4. Repository Structure
- `Lab6_Association_Mining.ipynb`: Main Jupyter Notebook containing data loading, preprocessing, mining, and visualizations.
- `README.md`: Summary of lab objectives, results, and lessons learned.
