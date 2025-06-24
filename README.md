# GitHub API Data Collection Notebook

This Jupyter notebook demonstrates how to interact with the GitHub API to collect and analyze repository data. It's designed as part of a Data Source API Analyst homework assignment for Improvado.

## 📋 Overview

The notebook provides a comprehensive implementation for:
- Connecting to GitHub's REST API
- Collecting repository information
- Fetching commit data with filtering capabilities
- Data transformation and export functionality
- Error handling and logging

## 🚀 Features

- **GitHub API Integration**: Implementation of GitHub REST API calls
- **Authentication Support**: Optional GitHub token authentication for higher rate limits
- **Data Filtering**: Advanced filtering capabilities for API responses
- **Multiple Export Formats**: Save data as JSON or CSV files
- **Comprehensive Logging**: Detailed logging for debugging and monitoring
- **Error Handling**: Robust error handling for API failures
- **Rate Limiting**: Built-in handling for API rate limits

## 🔑 GitHub Token (Optional)

For enhanced functionality and higher rate limits:
1. Go to [GitHub Settings > Developer settings > Personal access tokens](https://github.com/settings/tokens)
2. Enter the token when prompted in the notebook

**Without token**: 60 requests per hour  
**With token**: 5,000 requests per hour

## 📊 Data Export

The notebook supports exporting collected data in multiple formats:
- **JSON**: Structured data with full API response
- **CSV**: Tabular format for analysis in Excel/other tools

All exports are saved to the `output/` directory with descriptive filenames.

### Google Colab
You can also access this notebook in Google Colab:
[Open in Google Colab](https://drive.google.com/file/d/13rv81Ws6jXz525IYJiFWuUxVb7FxkPQD/view?usp=sharing)

*Note: Some file operations may work differently in Colab environment.*

## 📝 Documentation

Additional documentation is available in the `Content/` directory:
- **Notebook Documentation Features and Functionality.pdf** - Detailed feature overview
- **About the creative process.pdf** - Development insights
