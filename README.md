# Mars Web Scraping and Data Analysis Project

**Description**: This project involves web scraping and data analysis of Mars-related information. The task is divided into two main parts: scraping Mars news articles and scraping and analyzing Mars weather data. The skills utilized include HTML parsing with Beautiful Soup, automated browsing with Splinter, and data manipulation with Pandas.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Description](#data-description)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Deliverables](#deliverables)
6. [Contributing](#contributing)
7. [License](#license)
8. [Contact](#contact)

## Introduction
In this project, we scrape data from two different Mars-related websites. First, we extract the latest news articles from the Mars News site. Second, we scrape Mars weather data from a table and analyze it to gain insights about Martian climate patterns.

## Data Description
### Part 1: Mars News Articles
- **Data Source**: Mars News website
- **Extracted Information**: Titles and preview text of news articles
- **Storage Format**: List of dictionaries

### Part 2: Mars Weather Data
- **Data Source**: Mars Temperature Data Site
- **Extracted Information**: Mars weather data (including terrestrial date, sol, solar longitude, month, minimum temperature, and atmospheric pressure)
- **Storage Format**: Pandas DataFrame

## Installation
To set up the project on your local machine, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd your-repo
   ```
3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
### Part 1: Scraping Mars News
Run the Jupyter Notebook `part_1_mars_news.ipynb` to scrape titles and preview text from the Mars News website. The results will be stored in a list of dictionaries and printed in the notebook.

### Part 2: Scraping and Analyzing Mars Weather Data
Run the Jupyter Notebook `part_2_mars_weather.ipynb` to scrape Mars weather data, convert it into a Pandas DataFrame, and perform analysis to answer various questions about Martian climate patterns.

### Exporting Data to Excel
Use the following code to export the DataFrame to an Excel file:
```python
import pandas as pd

# Export the DataFrame to an Excel file
df.to_excel('mars_data.xlsx', index=False)
```

## Deliverables
1. **Deliverable 1**: Jupyter notebook `part_1_mars_news.ipynb` containing code to scrape Mars news titles and preview text.
2. **Deliverable 2**: Jupyter notebook `part_2_mars_weather.ipynb` containing code to scrape and analyze Mars weather data.

## Contributing
If you wish to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.


## Contact
For any questions or feedback, please contact me at cortes.santiago.ca@gmail.com
