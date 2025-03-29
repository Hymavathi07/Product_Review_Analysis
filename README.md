# Product Review Analyzer

## Overview
Product Review Analyzer is a tool designed to extract, classify, summarize, and rate reviews from e-commerce platforms like Amazon and Flipkart. This project provides insights into product sentiment by analyzing customer reviews.

## Features

### Data Extraction
- Automatically fetches reviews from a given URL.
- Exports extracted reviews as a clean CSV file.

### Sentiment Classification
- Classifies each review into one of three categories:
  - Positive
  - Neutral
  - Negative

### Review Summarization
- Generates a concise summary of all reviews for quick insights.

### Overall Rating
- Calculates an overall rating based on sentiment polarity.

### Top Reviews Showcase
- Displays the top five reviews in each sentiment category:
  - Top 5 Positive
  - Top 5 Neutral
  - Top 5 Negative

### Product Analysis
- Determines whether the product is:
  - Good
  - Okay
  - Bad

## Technologies Used
- Python for data extraction, sentiment analysis, and summarization
- Natural Language Processing for sentiment classification
- Pandas for data manipulation and CSV export
- Matplotlib and Seaborn for visualization (optional)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-url.git
   cd product-review-analyzer
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Run the application:
   ```bash
   python app.py
   ```
2. Provide the product review page URL when prompted.
3. View the extracted and analyzed data.

## Contributing
Contributions are welcome. Feel free to fork this repository and submit a pull request with improvements or bug fixes.

## License
This project is licensed under the MIT License.

## Contact
For any inquiries, please reach out via email or open an issue in the repository.
