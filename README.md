# Beyond the Buzzer

Beyond the Buzzer is your one-stop shop for comprehensive NBA player statistics and insightful visualizations. Fueled by the power of Python and web scraping with BeautifulSoup, we provide a platform for NBA enthusiasts to explore a player's performance beyond the final score.

## Key Features

- **Comprehensive Player Stats**: Access detailed statistics on NBA players, including points, assists, rebounds, shooting percentages, and more.
- **Advanced Visualizations**: Gain insights with visualizations that go beyond basic stats, providing an in-depth analysis of player performance.
- **Web Scraping**: Automated data collection from trusted sources using Python and BeautifulSoup to keep player statistics up to date.
- **User-Friendly Interface**: Simple navigation and presentation of stats and charts, making it easy for users to explore and analyze player data.

## Technologies Used

- **Python**: The core programming language used for data processing and analysis.
- **BeautifulSoup**: A Python library for web scraping player stats from external sources.
- **Matplotlib/Seaborn**: Libraries for creating insightful visualizations from the gathered data.
- **Pandas**: For handling and processing large datasets efficiently.

## Project Structure

- **scraper/**: Contains Python scripts for scraping NBA player statistics.
  - **scrape.py**: Main script for collecting data from web sources using BeautifulSoup.
- **visualizations/**: Scripts for generating statistical charts and graphs.
  - **plot_stats.py**: Python script that processes scraped data and generates visualizations using Matplotlib/Seaborn.
- **data/**: Stores the scraped datasets for easy access and analysis.
  - **player_stats.csv**: CSV file containing processed player data.

## Requirements

- **Python 3.x**
- **BeautifulSoup** (for web scraping)
- **Pandas** (for data manipulation)
- **Matplotlib** / **Seaborn** (for visualizations)
