# NCFpyproject
final project
# COVID-19 News Analysis with GDELT

This project analyzes COVID-19-related articles using natural language processing (NLP) and machine learning models. The dataset is sourced from the [GDELT](https://blog.gdeltproject.org/gdelt-2-0-our-global-world-in-realtime/) COVID-19 database, which tracks global news articles. The project leverages several techniques, including word frequency analysis, semantic search using embeddings, and dimensionality reduction for visualizations.

## Features

- **Data Collection**: Queries COVID-19-related data from the GDELT database using BigQuery.
- **Text Preprocessing**: Cleans and organizes the data by removing duplicates, normalizing text, and filtering articles by keywords (e.g., vaccine-related terms).
- **Word Frequency Analysis**: Identifies and ranks the most frequent words by topic, with an option to explore top words per topic.
- **Semantic Search**: Uses sentence embeddings to perform semantic search, finding similar articles based on a given query.
- **Dimensionality Reduction & Visualization**: Reduces the dimensionality of text embeddings using UMAP for 2D visualization, showing topic clusters.
- **Interactive Interface**: Built using Gradio, enabling users to interact with the model and view search results and visualizations.


