# Yelp Review Bias Detection

This project identifies and analyzes patterns of biased or discriminatory language within Yelp reviews from the [Yelp Open Dataset](https://business.yelp.com/data/resources/open-dataset/). Reviews and business data were first combined into structured CSV files, focusing on approximately 12,000 reviews per city. Text preprocessing produced a clear `clean_text` column for detailed analysis. Reviews underwent toxicity scoring and a custom bias-similarity assessment, with ambiguous cases manually reviewed and labeled (`is_biased`).  

Analysis highlights:
- Hotels exhibit significantly higher bias rates compared to restaurants or spas.
- Bias incidents show clear seasonal trends and geographic clustering.

Future plans include sentiment analysis integration to better categorize bias types and refine automated detection processes, aiding proactive moderation efforts.

**Dataset**: [Yelp Open Dataset](https://business.yelp.com/data/resources/open-dataset/)

**Techniques Used**: Data preprocessing, Toxicity scoring, Bias similarity metrics, Exploratory Data Analysis, LDA Topic Modeling
