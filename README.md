# YouTube
## Summary of the YouTube data analysis
### Problematic analyzed
The project focuses on gaining a better understanding of audience interaction and behavior on YouTube videos. It analyzes how factors such as likes, dislikes, comments, and emojis affect video views and seeks to determine whether the audience is entertained​​.

### Technologies used
- Python and Jupyter Notebooks: For data manipulation and analysis development.
- Pandas: For data handling.
- TextBlob: For sentiment analysis.
- String: For punctuation analysis.
- Data Visualization: Tools such as matplotlib and seaborn were used to create charts and visualize patterns in the data..

### Functions used
- TextBlob().sentiment: To analyze the sentiment of comments.
- 'For' loop: To iterate through the comments and calculate the sentiment of each, storing the result in a new DataFrame column​​.

### Steps followed for data analysis
1. Data Import: Relevant data such as comments, likes, dislikes, and video views were imported.
2. Data Preprocessing: [2.1] The data was cleaned by removing null values and duplicates. [2.2] Text in the comments was tokenized and normalized.
3. Sentiment Analysis: TextBlob was used to analyze the sentiment of comments and emojis, classifying them as positive, negative, or neutral​​.
4. Audience Interpretation: The correlation between punctuation marks and the number of comments with the number of views was analyzed to understand the relationship between audience activity and video success​​.

### Visualization 
|----|----|
|![Imagen1]()|![Imagen2]()
|----|----|
|![Imagen3]()|![Imagen4]()
|![Imagen5]()|![Imagen6]()

### Analysis conclusions
- There is a significant correlation between positive comments and the number of video views, suggesting that an entertained and engaged audience tends to increase the popularity of the content.
- Punctuation marks and emojis in comments are useful indicators for determining the emotional interaction level of the audience.
- Combining sentiment analysis and audience behavior can provide valuable insights for content creators looking to optimize their strategy on YouTube​​.
