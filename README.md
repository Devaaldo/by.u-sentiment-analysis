# Bayu App Sentiment Analysis

A comprehensive sentiment analysis project that analyzes user reviews from the Bayu (by.U) mobile application using natural language processing and machine learning techniques.

## Overview

This project extracts and analyzes 227,588+ customer reviews from the Bayu telecommunications application to understand user sentiment, identify pain points, and evaluate customer satisfaction. The analysis includes data preprocessing, sentiment classification, and statistical insights on user feedback patterns.

## Dataset

- **Source**: Bayu (by.U) application reviews from Google Play Store
- **Records**: 227,588 reviews
- **Features**:
  - User reviews and ratings
  - Timestamps and version information
  - Official company responses
  - User engagement metrics (thumbs up count)

## Visualizations

### Word Cloud Analysis
![Word Cloud of User Reviews](images/wordcloud_reviews.png)

The word cloud above represents the most frequently occurring terms in all user reviews. Larger text indicates more frequently mentioned words, revealing common themes and pain points users discuss.

## Project Structure

- `bayu_sentimen_analysis.ipynb` - Complete analysis notebook including:
  - Data exploration and preprocessing
  - Text analysis and visualization (wordcloud, distribution plots)
  - Sentiment classification and modeling
  - Statistical insights and findings
- `ulasan_aplikasi.csv` - Dataset containing all review records
- `images/` - Visualizations and charts generated from analysis

## Methodology

The analysis workflow includes:

1. **Data Loading & Exploration** - Understanding dataset structure, size, and distribution
2. **Data Preprocessing** - Text cleaning, tokenization, normalization, and feature extraction
3. **Sentiment Analysis** - Classification of reviews into sentiment categories using machine learning
4. **Visualization** - Word frequency analysis, sentiment distribution, rating patterns
5. **Interpretation** - Key findings and actionable insights from the data

## Technologies Used

- **Python 3.x**
- **Jupyter Notebook** - Interactive analysis environment
- **pandas** - Data manipulation and analysis
- **scikit-learn** - Text processing and machine learning models
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Data visualization
- **WordCloud** - Word frequency visualization

## Key Insights

The sentiment analysis reveals:

- **Common User Issues**:
  - Application stability and performance problems
  - Network connectivity and signal issues
  - Payment and transaction errors
  - Data quota management concerns

- **User Sentiment Distribution**:
  - Mix of positive, negative, and neutral reviews
  - Recurring themes in user feedback
  - Correlation between issues and low ratings

- **Response Patterns**:
  - Company response rate and timing
  - Customer satisfaction impact of support responses

## How to Use

1. Clone the repository
   ```bash
   git clone https://github.com/Devaaldo/sentimen-bayu-app.git
   cd sentimen-bayu-app
   ```

2. Set up Python environment
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies
   ```bash
   pip install pandas scikit-learn numpy matplotlib seaborn wordcloud jupyter
   ```

4. Launch Jupyter and open the notebook
   ```bash
   jupyter notebook bayu_sentimen_analysis.ipynb
   ```

5. Run cells sequentially to reproduce the entire analysis

## Results

The notebook generates:
- Word clouds showing frequent terms in positive and negative reviews
- Sentiment distribution visualizations
- Statistical summaries and insights
- Recommendations based on analysis findings

## Author

Created for portfolio demonstration of data analysis and NLP capabilities.

## License

This project is for educational and analytical purposes.
